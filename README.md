# python-code-for-video-capturing
import cv2 , time
video=cv2.VideoCapture(0)
while True:
 check,frame=video.read()
 print(check)
 print(frame)
 cv2.imshow("capturing",frame)
 key=cv2.waitKey(1)
 if key==ord("q"):
  break
cv2.viedorelease()
cv2.destroyAllWindows
