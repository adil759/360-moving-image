# 360-moving-image
moving image code
.about-image {
  
 transform: translateX(-50%);
  animation: move 5s linear infinite;

}
@keyframes move {
  0% {
    transform: translate(-100px, 0) rotate(0deg);
  }
  100% {
    transform: translate(-100px, 0) rotate(360deg);
  }
}
