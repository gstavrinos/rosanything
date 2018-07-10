# ROSANYTHING!


Create custom commands that use autocomplete of ROS messages with ease!

:warning: WARNING:
---

The `install_rosanything` python script messes with your `.bashrc` file. Please use it at your own risk.

#
Currently, the removal of a custom command can be done only manually by deleting the shell script created inside the `bash` folder and removing the source command that was appended in `.bashrc`.


# Example of installation of two commands
`rosrun rosanything install_rosanything tail subl` 

(Notice that you do not need to add `ros` before the command you want to create. It will be added automatically, `rostail` and `rossubl` for the example above)
