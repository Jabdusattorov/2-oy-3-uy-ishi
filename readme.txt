/* RESET */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
  }
  
  img {
    max-width: 100%;
    max-height: 100%;
  }

  a {
    color: inherit;
    text-decoration: none;
  }
  
  ul {
    list-style: none;
  }
  
  body {
    font-family: sans-serif;
  }
  
  section {
    padding: 5rem 0;
     h2 {
      font-size: 48px;
      font-weight: 700;
      color: #000;
    }
    p{
      font-size: 16px;
      font-weight: 400;
      color: #000;
    }
    h5{
      text-transform: uppercase;
    font-size: 16px;
    font-weight: 400;
    text-align: center;
    letter-spacing: 2px;
    }
  }
  /* RESET end */
  
  /* UTILS */
  
  .container {
    width: 1400px;
    margin: 0 auto;
  }
  
  .flex {
    display: flex;
  }
  
  .align-start {
    align-items: flex-start;
  }
  
  .align-center {
    align-items: center;
  }
  
  .align-end {
    align-items: flex-end;
  }
  
  .align-stretch {
    align-items: stretch;
  }
  
  .justify-start {
    justify-content: flex-start;
  }
  
  .justify-center {
    justify-content: center;
  }
  
  .justify-end {
    justify-content: flex-end;
  }
  
  .justify-between {
    justify-content: space-between;
  }
  
  .justify-around {
    justify-content: space-around;
  }
  
  .justify-evenly {
    justify-content: space-evenly;
  }
  
  .justify-baseline {
    justify-content: baseline;
  }
  
  .portion {
    flex: 1;
  }
  
  .button {
    all: unset;
    box-sizing: border-box;
    display: inline-block;
    padding: 15px 28px;
    background-color: #0077c0;
    color: #fff;
    border-radius: 10px;
    text-transform: capitalize;
  }
  
  .button:hover {
    opacity: 0.9;
  }
  
  .button:active {
    opacity: 0.8;
  }
  
  /* UTILS end */
  
  /* Header#main-header */
  
  header#main-header {
    background-color: #fff;
    padding: 2rem 0;
    .logo.flex{
      gap: 3px;
    font-size: 24px;
    font-weight: 700;
    text-transform: capitalize;
    }
    ul.flex{
      gap: 2rem;
    }
  }
  /* Header#main-header end */
  
  /* section#showcase */
  
  section#showcase {
    background-color: #fff;
    padding-bottom: 0;
    h1 {
      font-size: 60px;
      font-weight: 700;
      line-height: 1.4;
    }
    p {
      width: 400px;
      margin: 1rem 0;
      line-height: 1.4;
    }
  }  
  /* section#showcase end */
  

  /* section#feature */
  section#feature {
    background-color: #0077c0;
    h2 {
      width: 480px;
      text-align: center;
      margin: 0 auto;
      margin-top: 1rem;
      margin-bottom: 5rem;
    }
    .flex {
      gap: 3rem;
    }
    span.icon-wrapper {
      background-color: #c7eeff;
      width: 110px;
      height: 110px;
      border-radius: 50%;
      display: inline-flex;
      align-items: center;
      justify-content: center;
    }
    h3 {
      margin: 1rem 0;
      font-size: 24px;
      font-weight: 700;
    }
    p {
    line-height: 1.4;
  }
  }
  section#feature * {
    color: #fff;
  }  
  /* section#feature end */

  
  /* section#steps */
  section#steps {
    background-color: #fff;
    .flex{
      gap: 5rem;
       }
    h2 {
    width: 550px;
    margin-bottom: 2rem;
  }
  ul {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    font-size: 16px;
    font-weight: 400;
    li {
      display: flex;
      align-items: center;
    }
    span {
      background-color: #c7eeff;
      width: 32px;
      height: 32px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      border-radius: 50%;
      margin-right: 1rem;
    }
  }
}
  /* section#steps end */

  
  /* section#explore */
  section#explore {
    background-color: #c7eeff;
    padding-bottom: 0;
    .flex {
      gap: 5rem;
    }
    h2 {
      width: 560px;
    }
    p {
      width: 500px;
      margin: 2rem 0;
      line-height: 1.4;
      word-spacing: 1px;
    }
  }
  /* section#explore end */

  // section#test
  section#test{
    text-align: center;
    h4{
      color: rgba(0, 119, 192, 1);
      font-size: 16px;
    }
    h2{
      font-size: 48px;
      line-height: 60px;
    }
    .box{
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 0px 100px;
      align-items: flex-start;
      .card{
        width: 360px;
        text-align: left;
        padding: 20px;
        vertical-align: top;
      }
      .user{
        display: flex;
        align-items: center;
        img{
          width: 48px;
          height: 48px;
          border-radius: 50%;
        }
        .user-name{
          padding-left: 10px;
          h6{
            font-size: 16px;
            line-height: 20px;
          }
          i{
            color: gold;
            font-size: 12px;
            margin: 5px 5px 0px 0px ;
          }
        }
      }
      .user-text{
        p{
          margin-top: 20px;
          font-size: 16px;
          line-height: 28px;
          font-weight: 400;
          font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }
      }
    }
  }
  // section#test end

  /* footer#main-footer */
  footer#main-footer {
    background-color: #1d242b;
    color: #fff;
    padding: 5rem 0;
    .logo + nav {
      margin: 1rem 0;
    }
    .logo + nav li {
      background-color: rgba(255, 255, 255, 0.2);
      display: inline-flex;
      width: 32px;
      height: 32px;
      border-radius: 50%;
      align-items: center;
      justify-content: center;
    }
    .portion:nth-child(1) {
      width: 20%;
      flex: auto;
      margin-right: 100px;
    }
    .pages li {
      margin-top: 1rem;
      text-transform: capitalize;
    }
    form {
      margin-top: 2rem;
    }
     button, input {
    border: none;
    background: none;
  }
  }
  /* footer#main-footer end */
  