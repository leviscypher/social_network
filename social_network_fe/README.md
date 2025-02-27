/social-network-app
│── /public                # Thư mục chứa favicon, hình ảnh, file tĩnh
│── /src                   
│   ├── /assets            # Chứa hình ảnh, icon, file tĩnh
│   ├── /components        # Các component dùng chung
│   │   ├── Navbar.jsx
│   │   ├── Sidebar.jsx
│   │   ├── Button.jsx
│   │   ├── Modal.jsx
│   │   ├── Spinner.jsx
│   │   ├── ProtectedRoute.jsx  # Bảo vệ route
│   │   ├── ThemeSwitcher.jsx    # Chuyển đổi theme
│   │── /layouts           # Layouts cho User và Admin
│   │   ├── UserLayout.jsx
│   │   ├── AdminLayout.jsx
│   ├── /pages             # Các trang chính
│   │   ├── /auth          # Các trang xác thực
│   │   │   ├── Login.jsx
│   │   │   ├── Register.jsx
│   │   │   ├── ForgotPassword.jsx
│   │   ├── /user          # Các trang dành cho User
│   │   │   ├── Home.jsx
│   │   │   ├── Profile.jsx
│   │   │   ├── Settings.jsx
│   │   │   ├── Messages.jsx
│   │   │   ├── Friends.jsx
│   │   │   ├── PostDetail.jsx
│   │   │   ├── Search.jsx
│   │   ├── /admin         # Các trang dành cho Admin
│   │   │   ├── Dashboard.jsx
│   │   │   ├── UserManagement.jsx
│   │   │   ├── PostManagement.jsx
│   │   │   ├── Reports.jsx
│   │   │   ├── Analytics.jsx
│   ├── /redux             # Redux Toolkit store
│   │   ├── store.js       # Store chính
│   │   ├── authSlice.js   # Xử lý trạng thái xác thực
│   │   ├── userSlice.js   # Quản lý thông tin người dùng
│   │   ├── postSlice.js   # Quản lý bài đăng
│   │   ├── messageSlice.js# Quản lý tin nhắn
│   ├── /hooks             # Custom hooks
│   │   ├── useAuth.js
│   │   ├── useFetch.js
│   ├── /services          # Giao tiếp API
│   │   ├── api.js         # Cấu hình Axios
│   │   ├── authService.js
│   │   ├── userService.js
│   │   ├── postService.js
│   │   ├── messageService.js
│   ├── /utils             # Chứa các function tiện ích
│   │   ├── formatDate.js
│   │   ├── validateForm.js
│   ├── /styles            # CSS/Tailwind Styles
│   │   ├── globals.css
│   ├── /routes            # Cấu hình Routes
│   │   ├── AppRoutes.jsx
│   ├── main.jsx           # File gốc mount React
│   ├── App.jsx            # Component chính của app
│── package.json           # Cấu hình dependencies
│── vite.config.js         # Cấu hình Vite
│── tailwind.config.js     # Cấu hình Tailwind CSS
│── .eslintrc.js           # Cấu hình ESLint
│── .gitignore             # Git Ignore
│── README.md              # Hướng dẫn sử dụng
