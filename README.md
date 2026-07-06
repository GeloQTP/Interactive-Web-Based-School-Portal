# Modern Student Portal

An interactive, social-media-like college portal built with PHP, MySQL, and Bootstrap. This project demonstrates a modern, role-based web application where Students, Alumni, Teachers, and Admins can interact, share posts, and manage user information.

## Key Features

- Role-based access: `Student`, `Alumni`, `Teacher`, `Admin`.
- Posts, likes, and comments with admin moderation.
- User profiles with configurable public badge visibility.
- Admin badge management: assign badges to users from the admin UI.
- Curriculum, schedules, grades, and messaging components.
- Lightweight APIs under `/api/` for single-purpose endpoints.

## Admin workflow for badges
Sample Admin Account: TRCAdmin@gmail.com; Password: 123
1. Go to `public/admin/Pages/UserManagement.php` (Admin only).
2. Click the award icon in the Actions column to open the Badge Manager modal.
3. Create a badge (icon, description, date) and assign it; the modal lists assigned badges.
