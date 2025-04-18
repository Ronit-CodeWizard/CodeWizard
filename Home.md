<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>CodeWizard Projects</title>
  <style>
    body {
      margin: 0;
      padding: 2rem;
      background: linear-gradient(135deg, #fdfcfb 0%, #e2d1c3 100%);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    .header-container {
      position: relative;
      text-align: center;
      margin-bottom: 3rem;
    }

    h1 {
      font-size: 3.2rem;
      background: linear-gradient(to right, #6a11cb, #2575fc);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      font-weight: 900;
      letter-spacing: 2px;
      margin-bottom: 0.5rem;
      text-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      position: relative;
      z-index: 1;
    }

    .subheading {
      font-size: 1.1rem;
      color: #555;
      font-style: italic;
      margin-bottom: 1.5rem;
      z-index: 1;
      position: relative;
    }

    .header-container::before,
    .header-container::after {
      content: "";
      position: absolute;
      width: 100px;
      height: 100px;
      border-radius: 50%;
      background: radial-gradient(circle, #d1c4e9, #b39ddb);
      z-index: 0;
      opacity: 0.4;
    }

    .header-container::before {
      top: -40px;
      left: -50px;
    }

    .header-container::after {
      top: -40px;
      right: -50px;
    }

    .projects-wrapper {
      max-width: 800px;
      margin: auto;
      display: flex;
      flex-direction: column;
      gap: 1.5rem;
    }

    .project-card {
      background: linear-gradient(to right, #f0f8ff, #d0eaff);
      padding: 1.5rem;
      border-radius: 12px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .project-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 14px rgba(0, 0, 0, 0.2);
    }

    .project-name {
      font-size: 1.3rem;
      font-weight: 600;
      color: #34495e;
    }

    .button-group {
      display: flex;
      gap: 0.5rem;
    }

    .button-group button {
      background-color: #ffd86b;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 6px;
      cursor: pointer;
      font-weight: 600;
      transition: background-color 0.3s ease, transform 0.1s ease;
    }

    .button-group button:hover {
      background-color: #ffcf3b;
    }

    .button-group button:active {
      transform: scale(0.95);
    }

    @media (max-width: 600px) {
      .project-card {
        flex-direction: column;
        align-items: flex-start;
        gap: 1rem;
      }

      .button-group {
        width: 100%;
        justify-content: flex-start;
      }
    }
  </style>
</head>
<body>

  <div class="header-container">
    <h1>CodeWizard</h1>
    <p class="subheading">Crafting Cool Projects, One Line at a Time</p>
  </div>

  <div class="projects-wrapper">
    <div class="project-card">
      <div class="project-name">Animated Input Field</div>
      <div class="button-group">
        <button>Live Demo</button>
        <button>Source Code</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-name">CSS Tab Indicator</div>
      <div class="button-group">
        <button>Live Demo</button>
        <button>Source Code</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-name">Dark Text Animation</div>
      <div class="button-group">
        <button>Live Demo</button>
        <button>Source Code</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-name">Dropdown Menu</div>
      <div class="button-group">
        <button>Live Demo</button>
        <button>Source Code</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-name">Impossibly Tipsy Animation</div>
      <div class="button-group">
        <button>Live Demo</button>
        <button>Source Code</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-name">Modern Contact Card</div>
      <div class="button-group">
        <button>Live Demo</button>
        <button>Source Code</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-name">SVG Animated Footer</div>
      <div class="button-group">
        <button>Live Demo</button>
        <button>Source Code</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-name">Smooth Card Animation</div>
      <div class="button-group">
        <button>Live Demo</button>
        <button>Source Code</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-name">Tab Menu Bar</div>
      <div class="button-group">
        <button>Live Demo</button>
        <button>Source Code</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-name">Text Water Effect</div>
      <div class="button-group">
        <button>Live Demo</button>
        <button>Source Code</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-name">Truck Loader</div>
      <div class="button-group">
        <button>Live Demo</button>
        <button>Source Code</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-name">Valentine Day Card</div>
      <div class="button-group">
        <button>Live Demo</button>
        <button>Source Code</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-name">Button Click Animation</div>
      <div class="button-group">
        <button>Live Demo</button>
        <button>Source Code</button>
      </div>
    </div>
  </div>

</body>
</html>
