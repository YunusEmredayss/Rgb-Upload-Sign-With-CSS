#<!--Rgb-Upload-Sign-With-CSS-->

#<!--HTML Code-->
<div class="loader"></div>

#<!--CSS Code-->
.loader {
    border: 16px solid rgba(255, 255, 255, 0.2);
    border-radius: 50%;
    width: 120px;
    height: 120px;
    animation: spin 2s ease-in-out infinite;
  }
  
  @keyframes spin {
    0% {
      transform: rotate(0deg);
      border-top-color: rgb(255, 0, 0);
    }
    16.66% {
      border-top-color: rgb(255, 165, 0);
    }
    33.33% {
      border-top-color: rgb(255, 255, 0);
    }
    50% {
      border-top-color: rgb(0, 128, 0);
    }
    66.66% {
      border-top-color: rgb(0, 255, 255);
    }
    83.33% {
      border-top-color: rgb(0, 0, 255);
    }
    100% {
      transform: rotate(360deg);
      border-top-color: rgb(178, 34, 34);
    }
  }
