project-root/
├── app/                          # Next.js App Router
│   ├── (auth)/                   # Auth route group
│   │   ├── login/
│   │   └── register/
│   ├── (dashboard)/              # Protected route group
│   │   ├── dashboard/
│   │   └── profile/
│   ├── api/                      # API Routes
│   │   ├── auth/
│   │   ├── users/
│   │   └── health/
│   ├── globals.css               # Global styles & design tokens
│   ├── layout.tsx                # Root layout
│   ├── loading.tsx               # Global loading UI
│   ├── error.tsx                 # Global error UI
│   └── not-found.tsx             # 404 page
├── components/                   # Reusable UI components
│   ├── ui/                       # shadcn/ui components
│   ├── auth/                     # Auth-related components
│   ├── common/                   # Shared components
│   └── forms/                    # Form components
├── lib/                          # Utility libraries
│   ├── supabase/                 # Supabase configuration
│   │   ├── client.ts             # Client-side Supabase
│   │   ├── server.ts             # Server-side Supabase
│   │   └── middleware.ts         # Auth middleware
│   ├── utils.ts                  # General utilities
│   ├── validations.ts            # Zod schemas
│   └── constants.ts              # App constants
├── types/                        # TypeScript type definitions
│   ├── database.ts               # Supabase generated types
│   ├── auth.ts                   # Auth-related types
│   └── api.ts                    # API response types
├── hooks/                        # Custom React hooks
├── middleware.ts                 # Next.js middleware for auth
├── supabase/                     # Database migrations & seeds
│   ├── migrations/
│   └── seed.sql
└── tailwind.config.js            # Tailwind configuration