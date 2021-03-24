const express = require('express');
const path = require('path');
express.static('public');

const app = express();
app.use(express.static(__dirname + '/public'));

app.get('/', (req, res) => {
  res.sendFile(path.join(__dirname, './public', 'index.html'));
});

app.get('/mobileEqualTemperamentMajorScale', (req, res) => {
  res.sendFile(path.join(__dirname, './public', 'mobileEqualTemperamentMajorScale.html'));
});

app.get('/mobileJustIntonationMajorScale', (req, res) => {
  res.sendFile(path.join(__dirname, './public', 'mobileJustIntonationMajorScale.html'));
});

app.get('/keyboardEqualTemperamentMajorScale', (req, res) => {
  res.sendFile(path.join(__dirname, './public', 'mobileEqualTemperamentMajorScale.html'));
});

app.get('/keyboardJustIntonationMajorScale', (req, res) => {
  res.sendFile(path.join(__dirname, './public', 'mobileJustIntonationMajorScale.html'));
});


// Start the server
const PORT = process.env.PORT || 8080;
app.listen(PORT, () => {
  console.log(`App listening on port ${PORT}`);
  console.log('Press Ctrl+C to quit.');
});
// [END gae_node_request_example]

module.exports = app;
