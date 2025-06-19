// server.js
const express = require('express');
const cors = require('cors');
const multer = require('multer');
const app = express();
const port = process.env.PORT || 5000;

app.use(cors());
app.use(express.json());

app.get('/', (req, res) => {
  res.send('MM Courier backend is running.');
});

app.listen(port, () => {
  console.log(`MM Courier server running on port ${port}`);
});
