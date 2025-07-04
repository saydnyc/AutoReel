javascript:(function() {
  const allVideos = document.querySelectorAll('video');
  
  allVideos.forEach((video, index) => {
    video.addEventListener('ended', () => {
      const nextVideo = allVideos[index + 1];
      if (nextVideo) {
        nextVideo.scrollIntoView({
          behavior: 'smooth',
          block: 'center'
        });
      }
    });
    video.autoplay = false;
  });
})();
