# Where’s My
## Decentralised Device Tracking Application

### 🎯Problem it solves

- Current device tracking applications are fully centralized, which poses a risk to the security of sensitive information like device location and metadata.

- The absence of cross-platform compatibility requires users to utilize separate applications for their Android and iOS devices.

- To address these concerns, there is a need for a more personalized device tracking solution that enables users to add and track all their devices at one place in a decentralized manner.

### ⚡About
- The "Where's My" app is a solution that enables users to monitor the locations of their devices, like mobile phones, headphones, speakers, laptops, and any other Bluetooth-enabled devices within their vicinity. 

- This ecosystem is hosted on blockchain and leverages Bluetooth to detect the location of a device within the network of other mobile devices that have the "Where's My" app installed and are signed into the WheresMy network. 

### Our USP:
- Decentralised device tracking reduces the risk of a single point of failure.
- Cross-platform compatibility allows device tracking irrespective of Android or iOS device.
- Live location tracking keeps users engaged on the app



### ⚙️Here’s how Where’sMy works:

Let's say you have the Where'sMy application installed on your smartphone. Upon successful sign-up, there are 2 tasks taking place simultaneously. Firstly, the device automatically transmits its own current location, periodic timestamps, and a unique device ID to the decentralized blockchain network. Secondly, the app is programmed to keep Bluetooth enabled while it remains installed on the device, which means it is constantly detecting nearby bluetooth devices and helping send their device IDs to the blockchain network.

Now, let’s say you just added your bluetooth headphones to the Where’sMy Network. In the event that you lose your headphones, you report the device as lost on the Where’sMy app. 

Meanwhile, all devices utilizing the Where'sMy app have Bluetooth enabled, allowing them to constantly detect and collect information about nearby Bluetooth devices. Here, Data confidentiality is automatic due to the use of Blockchain. The user/owner is fully incharge of all their data and devices. As a result, the last recorded location of your headphones will be promptly sent to your Where'sMy app when they are in range of another device utilizing the app.

If the device is turned off and subsequently stolen, the same procedure will be initiated as soon as the device turns back on, providing you with the latest recorded location, time, and date of activity.


We have provided options to play sound for mobile devices, making them easy to locate. Additionally the "Where's My" app provides a live map tracking feature, allowing users to monitor their devices' locations in real-time. Along with this, the app has a section that tracks all visited locations, including date and timestamps, to create a timeline or journey for a more personalized user experience.

Where’s My stands out from other device tracking applications due to it’s decentralised network, making it highly secure. We have also made the UI minimalistic and clutter-free. The app focuses on usability and is accessible to all smart phone users. It is cross platform and is built for iOS and android.

### 🔥Challenges Faced
**Understanding device permissions and limitations**: Inorder to track different devices, it is important to understand their configuration. We had to dig deeper into device IDs and Mac Addresses of Bluetooth enabled devices to understand how they can be tracked.

**Data Access issue**: We were struggling to hide location data in a manner that only the server and device owner can access it. Without this the location of every device would be compromised to other devices in the network. Finally we were able to overcome this through a simple ‘if’ condition to handle accessibility of data. We found it hilarious that we were struggling over this XD

**BLE Service** : All Bluetooth Low Energy Devices advertise themselves and this information is periodically scanned in the Background. The scanned results are pinged to the server and the server filters out the registered devices on the platform and updates their location on the chain. Creating this service was a difficult task.



## Market Research:
Here is Market Research on Device Tracking Apps, proving that Where’s My is the only decentralised solution that can truly help users manage their own devices securely.

### ✅Advantages:

- Decentralized architecture: Having a decentralized device tracking app reduces the risk of a single point of failure.

- Cross-platform compatibility: A cross-platform compatible device tracking app would be more convenient for users to track their devices regardless of the operating system they use.

- Personalized device management: The ability to add and manage multiple devices in a decentralized manner would provide a more personalized experience to users.

- Cost-effective: A decentralized device tracking app could offer a more cost-effective solution compared to centralized alternatives, as it eliminates the need for expensive servers and storage systems.

- Great User Experience - We care about our users. We’ve kept the user journey simple and easy, while also making the app minimal and attractive.

- Advanced features: Advanced features such as historical location data, geofencing, and push notifications further enhance the utility of our device tracking app.


### 👀Disadvantages:
- It is mandatory for users to have a metamask wallet app. If not installed, the app redirects to playstore / appstore. It can be hard to promote among non-technical users which can limit adoption.

- If a device is destroyed after being reported as lost, the device remains lost on the app. However, this feature is considering the possibility that the device is ultimately found.

### 📈Business Model:
The basic version of the app would be free for usage. We will be providing Premium subscription for users who want to add more than 4 devices on the Where’sMy Network.
Higher subscription packs would include features like customizable App colours & themes and phone locking.


### ⏳Future Enhancements:

- Syncing Photos with User Timeline: This feature will allow users to view all of their visited locations with the photos taken at those locations.

- User Tracking Awareness: This enhancement will enable users to identify other Where'sMy App users who are monitoring their device, providing enhanced security and transparency.

- Location Data Integration: Integrating data from various sources, such as GPS, Wi-Fi, and cell tower triangulation, to provide accurate and detailed location information.

- Personalized Notifications: This feature will allow users to configure custom alerts and notifications based on their preferred settings, such as specific locations or time of day.

- User Analytics Dashboard: A user dashboard to display detailed analytics, such as time spent on each device, frequency of travel to certain locations etc.


### Conclusion

We have a strong conviction that our app can provide immense value to users by allowing them to easily locate and track all their smart devices in one convenient place. Our app features live location tracking, detailed user visit and timeline information, and a sleek, user-friendly interface that promises to offer a fun and engaging experience.

While there has been some research in this field, Where'sMy App stands out as the first decentralized device tracking app implemented. Our ultimate goal is to bring this app to a larger audience and continuously improve and grow our Where'sMy network.

We are team Chicken Wings with team members [Sandeep](http://github.com/thisissandeepkumar), [Pranav](https://github.com/pranavms13), [Nikitha](https://github.com/NikithaM26) and [Raksha](https://github.com/raksha-s). We hope you enjoy using the app. Thank you
