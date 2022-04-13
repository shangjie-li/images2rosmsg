# images2rosmsg

A Python tool for converting images into ROS topics

## Requirements
 - Clone this repository
   ```
   git clone git@github.com:shangjie-li/images2rosmsg.git
   ```
 - Install dependencies
   ```
   pip install catkin_tools
   pip install rospkg
   ```

## Usages
 - Convert images into ROS topics
   ```
   python images2rosmsg.py --images1=img_rgb --images2=img_t --pub_topic1=/pub_rgb --pub_topic2=/pub_t
   ```
 - Select images
   ```
   python select_images.py --input_folder1=img_rgb --input_folder2=img_t --output_folder1=visible --output_folder2=lwir
   ```
 - Convert JPG images into PNG images
   ```
   python jpg2png.py --input_folder=images_jpg --output_folder=images_png
   ```
 - Check images
   ```
   python check_images.py --image=my_image
   python check_images.py --images=my_images
   ```
