## Approximate analogies between iOS and Android development platforms

|     iOS       		|     Android     	| Description   |
|:-----------------:|:-----------------:|:-------------:|
 Xcode	      			| Android Studio     |  IDE           
 CocoaPods     		| ~Gradle	                 | build automation tool/dependency manager etc 
 iOS Simulator 		| Android Emulator          | virtual device for testing 
 Interface Builder 	| Layout Editor        | visual UI editor 
 Info.plist			| Manifest.xml             | project config file 
 AppDelegate   		| ~Activity/MainApplication | global class for managing app state 
 ViewController		| ~Activity/Fragment        | Class responsible for UI by default in MVC 
 View          		| Layout/View               | basic element for UI component representation 
 UIConstraint			| LayoutConstraint	| entity defining UI elements size and position
 UITableView/UICollectionView| RecyclerView    | UI grid for showing serial chunks of data
 UITableViewCell 	| Item/ViewHolder        |single view for item in RecyclerView
 UITableViewDataSource| RecyclerView.Adapter |class handling data source for RecyclerView
 UITabBar 			| BottomNavigation    | UI pattern with tabs swithching screens
 UINavigationController | SupportFragmentManager | handles stacks of Fragments, including transition, passing data and transition animations
 UIButton 		| Button/ImageButton  | pressable button with text or image atop
 UIImageView 		| ImageView   		  | UI element displaying images 
 UILabel 			| TextView        	  |  UI element showing text
 UITextField 		| EditText        	  |  UI element with editable text 
 IBOutlet 		| ~LayoutInflater/inflate() | helps referencing UI elements in code 
 UserDefaults		| SharedPreferences | insecure but simple to use storage for saving primitive, not serial types of data
 UIImage				| Bitmap 				| Class containing image data
 SwiftUI			| Compose 			| Framework for UI setup in declarative manner