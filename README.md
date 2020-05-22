# SDP- a scalable size unit
An android SDK that provides a new size unit - sdp (scalable dp). This size unit scales with the screen size. It can help Android developers with supporting multiple screens.

You can see that sdp scales with the screen size and the dp stays with the same size on all screen sizes.

Getting Started
To add sdp to your project (Using Android Studio and Gradle):

add implementation 'com.github.techreinforce:SDP:1.0.0' to your build.gradle dependencies block.

for example:

dependencies {

  implementation 'com.github.techreinforce:SDP:1.0.0'
  
} 

See the sdp_example.xml to see how to use to the sdp size unit.

For easy mapping of designs to sdp units, one can create designs with 300 pixels screen width - in this case each pixel in the design corresponds to 1 sdp.

Note
The sdp size unit calculation includes some approximation due to some performance and usability constraints.
