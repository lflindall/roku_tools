# roku_tools
Roku tools written in golang with command line execution

./roku -ip=10.1.13.221 -query=true -home=true -launch=dev

Usage of ./roku:  

  -home string  
      (-home=true to go home)
      
  -ip string  
      (-ip=10.1.13.221 (default "ipaddress"))   
      
  -launch string   
      (-launch=app_id found running -query=true i.e.dev, 2213  (default "app_id"))    
      
  -query string   
      (-query=true to query channels on device)  
      
  -send string    
      (-send=text string to enter  (default "none"))    
