# Calendar-App-Code
// Entry point for the Calendar Application 
// Frameworks used: React.js, Redux, and Tailwind CSS

import React from 'react';
import ReactDOM from 'react-dom';
import { Provider } from 'react-redux';
import { store } from './store';
import App from './App';

ReactDOM.render(
  <Provider store={store}>
    <App />
  </Provider>,
  document.getElementById('root')
);

