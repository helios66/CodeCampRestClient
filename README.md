# Rest Client for Code Camp
---

## Make a 'GET' call to url example
---

```java
		String url = "http://www.someurl.com";
		RestClient client = new RestClient(url);
		client.AddParam("key", "value");
		client.AddParam("keyOne", "valueOne");
		 
		 try{
			 	client.Execute(RequestMethod.GET);

				String response = client.getResponse();
		 }catch(Exception b){
			 
		 }
```

## Make a 'POST' call to url example
---

```java
		String url = "http://www.someurl.com";
		RestClient client = new RestClient(url);
		client.AddParam("key", "value");
		client.AddParam("keyOne", "valueOne");
		 
		 try{
			 	client.Execute(RequestMethod.POST);

				String response = client.getResponse();
		 }catch(Exception b){
			 
		 }
```