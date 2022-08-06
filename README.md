# AsyncOperation
Asynchronous Operation class based on NSOperation

# Description
Use this class to create a custom class by inheriting it and making the class to perform asynchronous operation.

# Usage
class CustomClass: AsyncOperation {

 override func cancel() {
 
   super.cancel()
   
  //Cancel the operation
  
 }
  
  override func main() {
  
   // Perform the task
   
  }

}

  override func finish() {
  
    super.finish()
    
    //Perform any sub-task after the operation is finished
    
  }
