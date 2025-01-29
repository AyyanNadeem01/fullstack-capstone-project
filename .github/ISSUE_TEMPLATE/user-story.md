1. User Registration & Login (New)
As a new user,
I want to register an account and log in securely,
So that I can access the platform and manage my listings.

Acceptance Criteria:

Users can register with a username, email, and password.
Passwords are securely stored using hashing.
Users receive an authentication token upon successful login.
2. Listing an Item (New)
As a registered user,
I want to create a new listing with details like title, description, category, and images,
So that others can see the items I am giving away.

Acceptance Criteria:

Users can add, edit, or delete their own listings.
Images can be uploaded with each listing.
Listings should be stored in the MongoDB database.
3. Searching for Items (New)
As a user,
I want to search for available household items using keywords, categories, and location,
So that I can find items that match my needs.

Acceptance Criteria:

A search bar allows users to filter results.
The search API returns relevant items from the database.
Items are displayed with key details like title, image, and availability.
4. User Profile Management (New)
As a registered user,
I want to edit my profile information such as name, profile picture, and bio,
So that other users can learn more about me.

Acceptance Criteria:

Users can update their profile details.
Changes are stored and displayed in real-time.
Profiles show listings associated with the user.
5. Sentiment Analysis for Comments (Technical Debt)
As a system,
I want to analyze the sentiment of user comments,
So that I can filter out negative or inappropriate content.

Acceptance Criteria:

A sentiment analysis API is integrated.
Comments are classified as positive, neutral, or negative.
Admins can review flagged negative comments.
6. Containerizing the Application (Technical Debt)
As a developer,
I want to containerize the application using Docker,
So that it can be easily deployed and scaled.

Acceptance Criteria:

The application runs inside a Docker container.
A Dockerfile is created for both frontend and backend.
Containers can be deployed using Kubernetes.
7. Implementing CI/CD Pipeline (Backlog)
As a developer,
I want to automate the deployment process using GitHub Actions and CI/CD,
So that changes are tested and deployed efficiently.

Acceptance Criteria:

A CI/CD pipeline runs on every push to the repository.
Automated tests are executed before deployment.
Successful builds are deployed to IBM Cloud.
8. Bookmarking Listings for Later (Icebox)
As a user,
I want to bookmark items I am interested in,
So that I can easily find them later without searching again.

Acceptance Criteria:

Users can add items to their favorites list.
The list is accessible from their profile page.
Items remain saved even after logging out.
