Laravel Beginner Task: Learn & Build CRUD App  
Objective:  
Read the official Laravel documentation and build a simple CRUD (Create, Read, Update, Delete) app in your own way.  
Step 1: Read the Laravel Documentation  
Go through the following sections of the official Laravel Docs:  
:books: https://laravel.com/docs (version 12)  
Focus on:  
- Routing  
- Controllers  
- Models & Migrations  
- Views (Blade)  
- Validation  
- Eloquent ORM  
  
Step 2: Implement a CRUD App  
Create a simple Laravel app to manage Posts.  
You can use any development environment (Laravel Sail, XAMPP, Valet, etc.) and any frontend style (Blade, Tailwind, Bootstrap, etc.).  
Database Structure for posts Table:  

  
| Field        | Type      | Notes                       |
| ------------ | --------- | --------------------------- |
| `id`         | Integer   | Primary key, auto-increment |
| `title`      | String    | Required                    |
| `content`    | Text      | Required                    |
| `status`     | Boolean   | 1 = published, 0 = draft    |
| `created_at` | Timestamp | Auto-managed by Laravel     |
| `updated_at` | Timestamp | Auto-managed by Laravel     |

  
Minimum Features to Implement:  
- Create new post  
- View all posts (list page)  
- Edit a post  
- Delete a post  
- Validation on form input  
  
Submission:  
Push your code to GitHub or GitLab and share the link for review.  
  
  
My dairy: 
July 11th:  
- Started a new Project
- Made an github repository
- Added class Post
- Made a One-to-Many relation between User and Post ( User HasMany Posts )
- Made a classic model for Post
- Made a controller for Post. You can create Posts and depending on status ( TODO: Add buttons like publish and save as a draft, if saved as a draft in request status is false, else pushed publish and status is true )
- Added Empty views for posts










