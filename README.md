<h1>Art Gallery Management System</h1>

<p>
  The <strong>Art Gallery Management System</strong> is a full-stack web application built using the <strong>MERN stack</strong> (MongoDB, Express.js, React.js, Node.js). It provides a platform for managing artworks, artists, exhibitions, and enables a seamless auction/bidding experience for customers and administrators.
</p>

<h2>Features</h2>
<ul>
  <li>Artwork management (add, update, delete, and view artworks)</li>
  <li>Exhibition scheduling and management</li>
  <li>Artist and customer profile management</li>
  <li>Bidding and auction system for artworks</li>
  <li>Payment slip upload and verification</li>
  <li>Admin dashboard for managing users, auctions, and payments</li>
  <li>Responsive and user-friendly interface</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li><strong>MongoDB</strong> - NoSQL database for storing application data</li>
  <li><strong>Express.js</strong> - Backend web framework for Node.js</li>
  <li><strong>React.js</strong> - Frontend library for building user interfaces</li>
  <li><strong>Node.js</strong> - JavaScript runtime for backend development</li>
</ul>

<h2>Getting Started</h2>
<ol>
  <li>
    <strong>Clone the repository:</strong>
    <pre><code>git clone &lt;repository-url&gt;</code></pre>
  </li>
  <li>
    <strong>Install dependencies:</strong>
    <ul>
      <li>Backend:
        <pre><code>cd ArtBackend
npm install</code></pre>
      </li>
      <li>Frontend:
        <pre><code>cd ../frontend
npm install</code></pre>
      </li>
    </ul>
  </li>
  <li>
    <strong>Configure environment variables:</strong>
    <ul>
      <li>Create a <code>.env</code> file in <code>ArtBackend/</code> and add your MongoDB URI and other necessary variables.</li>
    </ul>
  </li>
  <li>
    <strong>Run the backend server:</strong>
    <pre><code>cd ArtBackend
npm start</code></pre>
  </li>
  <li>
    <strong>Run the frontend app:</strong>
    <pre><code>cd frontend
npm start</code></pre>
  </li>
  <li>
    <strong>Access the application:</strong>
    <ul>
      <li>Frontend: <code>http://localhost:3000</code></li>
      <li>Backend API: <code>http://localhost:5000</code> (or as configured)</li>
    </ul>
  </li>
</ol>

<h2>Folder Structure Overview</h2>
<ul>
  <li><code>ArtBackend/</code> - Backend source code
    <ul>
      <li><code>Controller/</code> - Express route controllers (e.g., auctionController.js, paymentController.js)</li>
      <li><code>Model/</code> - Mongoose models (e.g., auctionModel.js, paymentModel.js)</li>
      <li><code>Route/</code> - API route definitions</li>
      <li><code>middleware/</code> - Custom middleware (e.g., error handling)</li>
      <li><code>Config/</code> - Database configuration</li>
      <li><code>uploads/</code> - Uploaded files (e.g., payment slips)</li>
      <li><code>server.js</code> - Entry point for the backend server</li>
    </ul>
  </li>
  <li><code>frontend/</code> - Frontend React application
    <ul>
      <li><code>src/Component/</code> - React components</li>
      <li><code>src/Context/</code> - React context for state management</li>
      <li><code>src/Pages/</code> - Page-level components</li>
      <li><code>public/</code> - Static assets</li>
      <li><code>package.json</code> - Frontend dependencies and scripts</li>
    </ul>
  </li>
</ul>

<h2>License</h2>
<p>
  This project is for educational purposes.
</p>
