# Software Engineering homework

Build and Run

        git clone https://github.com/Kento0k/KSoftwareEngineering.git
        gradle buildDocker
        docker run -p 8080:8080 org.example/SoftEng
Examples

        request: curl http://localhost:8080/?year=1998
        response: {"errorCode":200,"dataMessage":"13/09/1998"}
  
        request: curl http://localhost:8080/?currentDate=25042000
        response: {"errorCode":200,"dataMessage":"140"}
        
        request: curl http://localhost:8080?year=0  
        response: {"errorCode":200, "dataMessage":"INCORRECT INPUT"}
        
