# Cấu trúc thư mục dự án LinkUp
## Mô tả dự án
LinkUp là dự án mạng xã hội kết nối người dùng với nhau, giúp người dùng chia sẻ thông tin, bài đăng, kết bạn với nhau và nhắn tin trực tuyến (chat và video call). Dự án được xây dựng trên 2 nền tảng chính: Web và Mobile (Android). Frontend sử dụng NextJS và React Native (Expo), trong khi Backend sử dụng Gin Framework với ngôn ngữ Go, cơ sở dữ liệu sử dụng MySQL.

## Cấu trúc thư mục
Dưới đây là cấu trúc thư mục của dự án LinkUp (dạng phác thảo trước phát triển):

```
CAPSTONE-PROJECT/
└── sources/
    ├── backend/
    │   ├── cmd/
    │   │   └── main.go
    │   ├── config/
    │   │   └── env.go
    │   ├── controllers/
    │   │   ├── {controller_name}.go
    │   │   └── ...
    │   ├── models/
    │   │   ├── {model_name}.go
    │   │   └── ...
    │   ├── routes/
    │   │   └── routes.go
    │   ├── services/
    │   │   ├── {service_name}.go
    │   │   └── ...
    │   ├── repositories/
    │   │   ├── {repository_name}.go
    │   │   └── ...
    │   ├── utils/
    │   │   ├── {util_name}.go
    │   │   └── ...
    │   ├── db/
    │   │   ├── mysql.go
    │   │   └── ...
    │   ├── go.mod
    │   └── go.sum
    ├── frontend/
    │   ├── web/
    │   │   ├── components/
    │   │   │   ├── {component_name}.tsx
    │   │   │   └── ...
    │   │   ├── pages/
    │   │   │   ├── {page_name}.tsx
    │   │   │   └── ...
    │   │   ├── styles/
    │   │   │   ├── {style_name}.css
    │   │   │   └── ...
    │   │   ├── public/
    │   │   │   ├── images/
    │   │   │   └── ...
    │   │   ├── next.config.js
    │   │   ├── package.json
    │   │   └── ...
    │   └── mobile/
    │       ├── components/
    │       │   ├── {component_name}.tsx
    │       │   └── ...
    │       ├── screens/
    │       │   ├── {screen_name}.tsx
    │       │   └── ...
    │       ├── assets/
    │       │   ├── images/
    │       │   └── ...
    │       ├── app.json
    │       ├── package.json
    │       └── ...
    ├── README.md
    ├── CLAUDE.md
    └── AGENT.md
└── docs/       {tài liệu dự án (function, design, prompt huấn luyện AI, ...)}
    ├── project_proposal.md
    ├── design_document.md
    ├── testing_plan.md
    └── ...
```

## Công nghệ sử dụng:
**Backend:**
- Ngôn ngữ: Go
- Framework: Gin
- Cơ sở dữ liệu: MySQL

**Frontend:**
- Web: NextJS, React
- Mobile: React Native (Expo)