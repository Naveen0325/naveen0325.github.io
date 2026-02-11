import React from 'react';
import './F1Landing.css'; // we'll define styles below

const F1LandingPage: React.FC = () => {
  return (
    <div className="f1-page">
      {/* Top Navigation */}
      <header className="f1-header">
        <div className="logo">
          <img 
            src="https://www.formula1.com/etc/designs/fom-website/images/f1_logo.svg" 
            alt="Formula 1" 
            className="f1-logo"
          />
        </div>
        <nav className="f1-nav">
          <a href="#teams">About Teams</a>
          <a href="#schedule">Race Schedule</a>
          <a href="#tickets">Book Ticket</a>
        </nav>
      </header>

      {/* Hero Section */}
      <section className="hero">
        <div className="hero-background">
          {/* You can replace with real F1 racing image */}
          <img 
            src="https://images.unsplash.com/photo-1617814076367-b759c7d7e738?w=1600" 
            alt="F1 cars racing" 
            className="hero-image"
          />
        </div>

        <div className="hero-content">
          <h1>Welcome to F1</h1>
          <p className="subtitle">The pinnacle of motorsport</p>
        </div>
      </section>

      {/* Cards Section */}
      <section className="cards-section">
        <div className="cards-container">
          {/* Card 1 - Teams */}
          <div className="card">
            <div className="card-image-wrapper">
              <img 
                src="https://images.unsplash.com/photo-1505165494746-69f1d4b149c6?w=800" 
                alt="F1 cars on grid" 
              />
            </div>
            <div className="card-content">
              <h2>About Teams</h2>
              <p>Discover the 10 legendary teams competing in the 2025 season</p>
              <button className="card-button">CLICK HERE</button>
            </div>
          </div>

          {/* Card 2 - Schedule */}
          <div className="card">
            <div className="card-image-wrapper">
              <img 
                src="https://images.unsplash.com/photo-1544636331-b068134e5f1e?w=800" 
                alt="F1 race track" 
              />
            </div>
            <div className="card-content">
              <h2>Race Schedule</h2>
              <p>Full 2025 calendar – every Grand Prix, every date</p>
              <button className="card-button">CLICK HERE</button>
            </div>
          </div>

          {/* Card 3 - Tickets */}
          <div className="card">
            <div className="card-image-wrapper">
              <img 
                src="https://images.unsplash.com/photo-1581092160607-798e0a3a9d7c?w=800" 
                alt="F1 ticket" 
              />
            </div>
            <div className="card-content">
              <h2>Book Ticket</h2>
              <p>Get your seat for the most exciting races of the year</p>
              <button className="card-button">CLICK HERE</button>
            </div>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="f1-footer">
        <p>© {new Date().getFullYear()} Formula 1. All rights reserved.</p>
      </footer>
    </div>
  );
};

export default F1LandingPage;
