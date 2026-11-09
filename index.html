import (	
  "github.com/serpapi/serpapi-golang" 
  "fmt"
)

 func main() {

  setting := serpapi.NewSerpApiClientSetting("secret_api_key")
  client := serpapi.NewClient(setting)

  parameter := map[string]string{
    "engine": "google_light", 
    "q": "coffee",  }
  rsp, err := client.Search(parameter)

  if err != nil {
    fmt.Println("unexpected error", err)
    return
  }

  if rsp["search_metadata"].(map[string]interface{})["status"] != "Success" {
    fmt.Println("bad status")
    return
  }

  if rsp["organic_results"] == nil {
    fmt.Println("key is not found: organic_results")
    return 
  }

  if len(rsp["organic_results"].([]interface{})) < 5 {
    fmt.Println("expect more than 5 organic_results") 
    return
  }
}  
