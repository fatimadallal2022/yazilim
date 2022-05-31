# yazilim
import com.google.firebase.auth.FirebaseAuth

interface Authenticator{
  suspend fun signInWithEmailAndPassword(email:string.password:string)
  }
  class FirebaseAuthenticator"Authenticator{
  override suspend fun signInWithEmailAndPassword(email:string,password:string){
  FirebaseAuth.getInstance().signInWithEmailAndPassword(email,password)
  }
  }
