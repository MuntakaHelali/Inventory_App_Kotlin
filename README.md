Inventory Application - Solution 
==================================
This app is an stater code for an Inventory tracking app. Demos how to add, update, sell, and delete items from the local database.
This app demonstrated the use of Android Jetpack component [Room](https://developer.android.com/training/data-storage/room) database. The app also leverages [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel),
[LiveData](https://developer.android.com/topic/libraries/architecture/livedata),
[Flow](https://developer.android.com/kotlin/flow),
[View Binding](https://developer.android.com/topic/libraries/view-binding),
and [Navigation](https://developer.android.com/topic/libraries/architecture/navigation/)
with the SafeArgs plugin for parameter passing between fragments. 
<br>
<br>
When the user first starts the application, they will be presented with a screen that is blank with a floating action button(FAB) to add their items into the inventory list. Once the user selects on the FAB they will be displayed a screen where they can add the item name, price, and quantity. After inputting all the information, they have to click on save to add it to the local database on their device, and it will be displayed on the main inventory list screen. 
<br>
<br>
<p align="center">
 <img src="https://user-images.githubusercontent.com/57158277/169939275-3ff11f73-8055-4781-96dd-e6e388427dc1.png" width="250">
 <img src="https://user-images.githubusercontent.com/57158277/169939369-4a0d14f3-c762-49ed-abc2-e1b551cef138.png" width="250">
 <br>
 The above screenshot shows that the device already has some items stored in the inventory list.
</p>
<br>
<br>
If the user wanted to adjust an item they added, all they would have to do is simply click on the item. This action will lead the user to another screen showing details of the selected item, such as its name, price, and quantity. The FAB is provided to change information of the item, and options to sell and delete the item are also avaliable. 
<br>
<br>
<p align="center">
 <img src="https://user-images.githubusercontent.com/57158277/169940025-3f068bb6-3e05-4340-adc6-f68c04ba12a0.png" width="250">
 <img src="https://user-images.githubusercontent.com/57158277/169940106-c1921bd9-5c51-4645-a294-81628b2e7ebe.png" width="250">
 <img src="https://user-images.githubusercontent.com/57158277/169940170-cdbf8441-4f2d-4941-8870-a4f8eece030f.png" width="250">
</p>
<br>
<br>
Say the user wanted to sell the item, when they select the sell button, the quantity will be decreased by 1, and the change will be shown immediately. If the user wanted to get rid of the item entierly, all they would have to do is click on the delete button. They will then be prompted with a dialog box to make sure they are okay with deleting the item. By selecting "yes" in the dialog box, it will return the user to the inventory list screen and show the new list. 
<br>
<br>
<p align="center">
 <img src="https://user-images.githubusercontent.com/57158277/169940485-b16f171e-2421-4686-82d7-919d02d6b872.png" width="250">
 <img src="https://user-images.githubusercontent.com/57158277/169940541-8f8596c4-b2ce-4337-b132-e69b69b1d524.png" width="250">
 <img src="https://user-images.githubusercontent.com/57158277/169940849-08ea72a5-0558-479b-8348-fcdf48c55e0c.png" width="250">
</p>

