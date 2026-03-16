├── app/
│   ├── (auth)/              # Auth route group
│   │   ├── login/
│   │   └── register/
│   ├── (dashboard)/         # Protected route group
│   │   ├── dashboard/
│   │   └── profile/
│   ├── api/                 # API routes
│   │   ├── auth/
│   │   └── users/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── ui/                  # shadcn/ui components
│   ├── forms/              # Form components
│   ├── layouts/            # Layout components
│   └── common/             # Reusable components
├── lib/
│   ├── supabase/           # Supabase client & types
│   ├── validations/        # Zod schemas
│   ├── utils.ts           # Utility functions
│   └── constants.ts       # App constants
├── types/
│   ├── database.ts        # Database types
│   ├── auth.ts           # Auth types
│   └── api.ts            # API types
├── hooks/                 # Custom React hooks
├── middleware.ts          # Next.js middleware
└── supabase/
    ├── migrations/        # Database migrations
    └── seed.sql          # Initial data