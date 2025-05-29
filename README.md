// File: src/App.jsx (can be your only file)
import { StrictMode } from 'react';
import { createRoot } from 'react-dom/client';

// Main App Component
function App() {
  return (
    <main style={{
      display: 'flex',
      justifyContent: 'center',
      alignItems: 'center',
      minHeight: '100vh',
      backgroundColor: '#f5f5f5',
      margin: 0,
      fontFamily: 'Arial, sans-serif'
    }}>
      <h1 style={{
        fontSize: '3rem',
        color: '#333',
        textAlign: 'center'
      }}>
        Hello World
      </h1>
    </main>
  );
}

// Render the app
const container = document.getElementById('root');
const root = createRoot(container);
root.render(
  <StrictMode>
    <App />
  </StrictMode>
);
