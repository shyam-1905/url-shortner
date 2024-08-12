```markdown
# URL Shortener

A modern URL shortening application built with React and Supabase, offering URL shortening and comprehensive tracking metrics.

## Features

- Shorten long URLs to compact, shareable links
- Track usage metrics for shortened URLs
- Cross-platform analytics (desktop, mobile)
- User authentication and management via Supabase
- QR code generation for shortened URLs
- Responsive design for various devices

## Tech Stack

- **Frontend**: React 18
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **UI Components**: ShadCN
- **Routing**: React Router DOM
- **Database & Authentication**: Supabase
- **Charts**: Recharts
- **Form Validation**: Yup
- **Icons**: Lucide React
- **QR Code Generation**: react-qrcode-logo

## Prerequisites

- Node.js (v14 or later recommended)
- npm or yarn
- Supabase account and project set up

## Installation

1. Clone the repository:
```

git clone https://github.com/shyam-1905/url-shortener.git
cd url-shortener

```

2. Install dependencies:
```

npm install

```
or
```

yarn install

```

3. Create a `.env` file in the root directory and add your Supabase credentials:
```

VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key

```

## Development

To run the development server:

```

npm run dev

```
or
```

yarn dev

```

The application will be available at `http://localhost:5173` by default.





```

## Project Structure

- `src/`
  - `components/`: Reusable React components
  - `pages/`: Main page components
  - `lib/`: Utility functions and Supabase client
  - `hooks/`: Custom React hooks
  - `context/`: React context providers
  - `App.jsx`: Main application component
  - `main.jsx`: Entry point

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
