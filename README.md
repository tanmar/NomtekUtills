
# Nomtek Utills  
Collection of tools for android development.  
Detailed instructions are available in **How to use** sections.  
  
### How to install  
##### 1. Add jitpack repository to your gradle file 
```gradle  
allprojects {  
	repositories { ... 
		maven { url 'https://jitpack.io' } 
	} 
}
 ```  
  
##### 2. Add dependency to your gradle file  
  
###### ToolbarController  [How to use](https://github.com/nomtek/NomtekUtills/blob/master/toolbarcontroller/README.md)  
  
<img src="./resources/app.gif" width="250">  
  
```gradle  
implementation 'com.github.nomtek.NomtekUtills:toolbarcontroller:1.0.2'  
```   
###### StatusbarController  [How to use](https://github.com/nomtek/NomtekUtills/blob/master/statusbarcontroller/README.md) 
  
<img src="./resources/statusbar.gif" width="250">  
  
```gradle  
implementation 'com.github.nomtek.NomtekUtills:statusbarcontroller:1.0.2'  
```