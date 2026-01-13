# TaskGlitch

A Task Management Application for sales teams to track, manage, and prioritize tasks based on ROI.

## Features

- Add, edit, delete tasks
- Sort tasks by ROI
- Filter by status and priority
- Export to CSV
- Undo delete functionality
- Analytics dashboard

## Tech Stack

- React 18
- TypeScript
- Vite
- Material-UI
- Tailwind CSS (planned)

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Run development server: `npm run dev`
4. Build for production: `npm run build`

## Deployment

Deploy to Vercel or Netlify by connecting the GitHub repository.

## Bug Fixes Applied

1. **Double Fetch**: Removed duplicate data fetching useEffect.
2. **Undo Snackbar Logic**: Added clearLastDeleted function to properly clear state on snackbar close.
3. **Sort Stability**: Changed unstable Math.random() sort to stable title-based sort.
4. **Event Bubbling**: Added e.stopPropagation() to Edit and Delete buttons.
5. **ROI Validation**: Added checks for division by zero in computeROI.

## License

MIT
