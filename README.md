# ironsource
ironsource plugin for godot . modified from MrZak-dev's plugin


first download the file. then extract it.
install android build template into your project.
in the android>plugins folder paste the both .aar and .gdap file.
copy the "ironsource-plugin-api" file and paste the file under the res:// folder. 
now add the ironsource plugin node into your project . also add a timer node and name it "ads_cap".
autoload the ironsource.gd file.
now go to export setting then enable android custom build and ironsource plugin.
select your minimum sdk 22
edit android manifest from project\android\build\AndroidManifest.xml
      in the appliction tag insert the code     tools:replace="android:label"
create a scene. in the script under the ready function initialiaze the plugin by this way
func _ready():
	Ironsource._initialize()
  
  
 now make your own logic for move


![image](https://user-images.githubusercontent.com/92350126/156867066-4c9f0568-df9a-479d-909b-7695012417d9.png)
![image](https://user-images.githubusercontent.com/92350126/156867098-a172ea86-1cd0-49d9-a3d6-ed9d3bae03f9.png)

