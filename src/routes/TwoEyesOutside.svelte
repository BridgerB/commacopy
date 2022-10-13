<!-- <video class="video" autoplay muted loop>
  <source src="c3-hero.mp4" type="video/mp4">
</video> 



<p>two eyes outside</p>
<button>Buy Now</button> -->

<!-- <style>
  .video {
    width: 100%;
    height: 100%;
    
  }
  p {
    color: white;
  }

</style> -->

<div id="videoDiv"> 
  <video id="video1" autoplay muted loop>
    <source src="c3-hero.mp4" type="video/mp4">
  </video> 
  <div id="videoMessage" class="styling">
    <h1>two eyes outside</h1>
    <button>Buy Now</button>
  </div>
</div>

<style>
  #videoDiv {
    position: relative;
  }
  #video1 { 
    display: block;
    width: 100%;
  }
  #videoMessage { 
    position: absolute;
    top: 0;
    left: 0;
    display: flex;
    flex-direction: column; 
    justify-content: center;
    align-items: center; 
    width: 100%;
    height: 100%;
    color: white;
  }
</style>