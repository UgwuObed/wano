<template>
  <div class="outer-container">
    <div class="unauthorize-screen-container">
      <div class="logo-container">
        <img src="/img/Wanologo.png" alt="Wano Logo">
      </div>
      <div class="content-container">
        <div class="write-up">
          <h3>Unauthorized Access</h3>
          <p>This page can only be viewed from a mobile phone browser.</p>
        </div>
      </div>
      <div class="button-container">
        <button class="blue-button">Okay</button>
      </div>
    </div>
  </div>
  </template>

  <style>
  @import url('../assets/css/unauthorized.css');

  
  .outer-container {
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 149px;
  }

  .unauthorize-screen-container {
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  
  .logo-container {
    margin-bottom: 20px;
  }

  .logo-container img {
    width: 69.18px;
    height: 72.02px;
    left: 729.74px;
    top: 269px;
    

  }

  .content-container {
    background-color: #f7f7f7;
    padding: 20px;
    border-radius: 9.89006px;
    position: absolute;
    width: 410.4px;
    height: 169.54px;
    top: 267.85px;

  }
  
  .write-up h3 {
    margin-bottom: 20px;
    width: 220px;
    height: 26px;
    left: 481.84px;
    right: 300px;
    margin-left: 95px;
    margin-top: 30px;
    top: 541.25px;

    font-family: 'SF Pro Text';
    font-style: normal;
    font-weight: 600;
    font-size: 21.5294px;
    line-height: 26px;
    /* identical to box height */

    text-align: center;
    letter-spacing: -0.271977px;

    color: #AC3F02;

  }

  .write-up p {
    margin-bottom: 20px;
    width: 247.59px;
    height: 42px;
    left: 633.08px;
    margin-left: 85px;
    top: 468.93px;
    
    font-family: 'SF Pro Text';
    font-style: normal;
    font-weight: 400;
    font-size: 17.4926px;
    line-height: 21px;
    text-align: center;
    letter-spacing: -0.271977px;
    
    color: #000000;

  }
  
  .blue-button {
    background-color: #3D8AF7;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    border-radius: 40.3676px;
    border: none;
    width: 410.4px;
    height: 50.28px;
    margin-top: 270.14px;
    left: 478px;
    font-family: 'SF Pro Text';
    font-style: normal;
    font-weight: 500;
    font-size: 24.2206px;
    line-height: 29px;
    /* identical to box height */

    letter-spacing: -0.222022px;

    color: #FFFFFF;

  }
  

</style>