# Welcome to my Social media app : Soch 
I am using this and a few other repositories to show off some of the things i have learnt in the last year creating Frontend websites and usitlisng Nodes backend libraries to create some really cool stuff, i am also hoping to use them aswel in order to maintain and test these apps. 
https://www.youtube.com/watch?v=XxXyfkrP298&t=7154s


Thanks for Joining me at this point of my Journey 👍

 # Dev dependencies

 @sanity/client @sanity/image-url react-google-login react-icons react-loader-spinner react-masonry-css 
  react-router-dom uuid

`App.js`
import React from 'react'
// import img  from './Sosh.png'
// rafce

const App = () => {
  return (
    <>
    {/* <img src={img} alt="logo" /> */}
    <h1 className="text-3xl  underline">
      Hello world!
    </h1></>
    
  )
}

export default App


`index.css
@tailwind base;
@tailwind components;
@tailwind utilities;

body{
    font-family: 'Lato', sans-serif;
 
}


.hide-scrollbar::-webkit-scrollbar {
    display: none;
}

`index.js`
import React from 'react'
import ReactDOM from 'react-dom'
import App from './App';
import './index.css';
ReactDOM.render(<App />, document.getElementById('root'));



details
: 
"You have created a new client application that uses libraries for user authentication or authorization that will soon be deprecated.
 New clients must use the new libraries instead; 
 existing clients must also migrate before these libraries are deprecated. 
 See the [Migration Guide](https://developers.google.com/identity/gsi/web/guides/gis-migration) for more information."
error
: 
"idpiframe_initialization_failed"