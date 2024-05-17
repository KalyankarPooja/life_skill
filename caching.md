# Exploring Caching Approaches for Performance and Scalability
* Caching makes applications faster and more efficient by storing frequently used data closer to where it's needed, reducing the time to access this data. Here's an overview of different types of caching, along with their advantages and disadvantages.
Types of Caching :
### In-Memory Caching : Stores data in the computer's RAM,making access very fast.
### Distributed Caching : Uses multiple servers to store data, ensuring reliability and scalability.
### Client-Side Caching : Saves data on the users device,like a web browser.
### CDN Caching : Stores copies of static files like images and videos in various global locations,speeding up access.

### Advantage of using Caching :
* Improved performance : By using Caching we can access the frequently used data in less time and improves system performance and responsiveness.
* Reduced load on the original source : Reducing the access of data from original source ,improves the scalability and reliability.
* Cost saving : It reduces the use of expensive hardware device.
* Better User Experience : Faster data access leads to a smoother and quicker user experience.
* Scalability : Helps applications handle more users by offloading data requests from the main database.
* Availability : In distributed caching, if one server fails, others can still provide the cached data, ensuring reliability.

### DisAdvantage of using Caching :
* Data inconsistency : If cache consistency is not maintained properly, then rise issue in data consistency.
* Cache eviction issues : if eviction  policies are not designed properly then there be data loss.
* Additional Complexity : It makes system more diffcult to design, implement, and maintain.
* Storage Overhead : Caching requires additional storage space, which might be a concern in resource-limited environments.
* Security Risks : Cached data can be a security risk if not properly protected.
* Stale Data : There is a risk of serving outdated data if the cache is not properly updated.
* Configuration and Tuning * Effective caching requires careful setup and tuning to ensure optimal performance.

## Resources : https://www.geeksforgeeks.org/caching-system-design-concept-for-beginners/
