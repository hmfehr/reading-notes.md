# Local Storage and How To Use It On Websites

1. Why would a developer use local storage for a web application?
* it allows the website to be able to run clean but when a user has a login the computer can putt all the stored data for that user an to be able to pull it from the cookie.

2. What information should not be stored in local storage?
* The two primary risks when implementing these persistent storage features are letting hostile sites read information from other domains, and letting hostile sites write information that is then read from other domains.

* Letting third-party sites read data that is not supposed to be read from their domain causes information leakage. For example, a user's shopping wishlist on one domain could be used by another domain for targeted advertising; or a user's work-in-progress confidential documents stored by a word-processing site could be examined by the site of a competing company.

* Letting third-party sites write data to the persistent storage of other domains can result in information spoofing, which is equally dangerous. For example, a hostile site could add items to a user's wishlist; or a hostile site could set a user's session identifier to a known ID that the hostile site can then use to track the user's actions on the victim site.

3. Local storage can store what type of data? How would you convert it to that type before storing?
* local storage is that you can only store strings in the different keys. This means that when you have an object, it will not be stored the right way.
