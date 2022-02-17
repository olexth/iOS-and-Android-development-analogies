## Approximate analogies between iOS and Android development platforms

|     iOS       		|     Android     	| Description   |
|:-----------------:|:-----------------:|:-------------:|
 Xcode	      			| Android Studio     |  IDE           
 CocoaPods/Swift Package Manager     		| ~Gradle	                 | build automation tool/dependency manager etc 
 iOS Simulator 		| Android Emulator          | virtual device for testing 
 Interface Builder 	| Layout Editor        | visual UI editor 
 Info.plist			| Manifest.xml             | project config file 
 AppDelegate   		| ~Activity/MainApplication | global class for managing app state 
 ViewController		| ~Activity/Fragment        | Class responsible for UI by default in MVC 
 View          		| Layout/View               | basic element for UI component representation 
 NSLayoutConstraint			| LayoutConstraint | entity defining UI elements size and position
 UITableView/UICollectionView| RecyclerView    | UI grid for showing serial chunks of data
 UITableViewCell 	| Item/ViewHolder        |single view for item in RecyclerView
 UITableViewDataSource/Delegate| RecyclerView.Adapter |class handling data source/delegate for RecyclerView
 UITabBar 			| BottomNavigation    | UI pattern with tabs swithching screens
 UINavigationController | SupportFragmentManager | handles stacks of Fragments, including transition, passing data and transition animations
 UIButton 		| Button/ImageButton  | button with text or image atop
 UIImageView 		| ImageView   		  | UI element for displaying images 
 UILabel 			| TextView        	  |  UI element for showing text
 UITextField 		| EditText        	  |  UI element with editable text used with keyboard 
 IBOutlet 		| ~LayoutInflater/inflate() | reference to UI elements setup in editor in code 
 UserDefaults		| SharedPreferences | insecure but simple to use storage for saving primitive, not serial types of data
 UIImage				| Bitmap 				| class containing image data
 SwiftUI			| Jetpack Compose 			| declarative UI framework