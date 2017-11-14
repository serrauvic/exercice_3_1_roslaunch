# exercice_3_1_roslaunch
My first ros launch

Aquest packet de ROS simplement llença el node [usb_cam](https://github.com/ros-drivers/usb_cam), que a la seva vegada llença un image_view.

Aquest paquet te un únic paràmetre year amb valor 2017.

Els paràmetres de usb_cam són:

- **video_device**: On es diu quin *device* és la càmera de video. El valor per defecte és:"/dev/video0".
- **image_width**: Amplada de la imatge. El valor per defecte és: "640".
- **image_height**: Alçada de la imatge. El valor per defecte és: "480".
- **pixel_format**: Format dels píxels. Els valors possibles d'aquest paràmetre són: mjpeg, yuyv, uyvy. Per defecte el "yuyv".
- **camera_frame_id**: És un *string* que identifica la càmera "usb_cam".
- **io_method**: Mètode de sortida, possibles valors: mmap, read, userptr. El valor per defecte és:"mmap".
