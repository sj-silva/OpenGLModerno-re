# Modern OpenGL Essentials: First Steps Playlist

Welcome to the **Modern OpenGL Essentials: First Steps Playlist** playlist! This series of 31 short videos is designed to help you get started with graphical programming using OpenGL. Whether you're a beginner or someone looking to brush up on the fundamentals, this playlist will guide you through the essential concepts and techniques needed for 2D and 3D rendering.

## Playlist Overview

| **Video** | **Topics Covered** |
|-----------|---------------------|
| **[Video 1](https://youtu.be/MqIg2InJTKM?si=Qn4CiumsTw8yk-SN)** <br> Duration: 5:24 | - Installation of GLFW with vcpkg <br> - Drawing a triangle in Legacy mode <br> - Installation of GLEW |
| **[Video 2](https://youtu.be/-dK5QUrJX4E?si=feVAqpEvTSmxZDRY)** <br> Duration: 7:16 | - glGenBuffers <br> - glBindBuffer <br> - glBufferData |
| **[Video 3](https://youtu.be/P3PTqWFTvbU?si=dAM8Ain8dMaZ0Uso)** <br> Duration: 7:10 | - glVertexAttribPointer <br> - glEnableVertexAttribArray <br> - glDrawArrays <br> - Drawing a triangle at the end |
| **[Video 4](https://youtu.be/-P28LKWTzrI?si=o6-FW-ToZEPHOiEJ)** <br> Duration: 4:17 | - Graphics Pipeline <br> - NVidia Mythbusters Demo: GPU vs CPU |
| **[Video 5](https://youtu.be/BACQ1cdBHhk?si=JVZigkyZ-RBg_5V0)** <br> Duration: 5:28 | - Discussion of `Main.vert` and `Main.frag` (empty files) <br> - Creation of `Error.h` and `Error.cpp` |
| **[Video 6](https://youtu.be/KCEiHRvnbYs?si=4u_Lj5hCC44Pxj7L)** <br> Duration: 3:21 | - Vector and point operations <br> - Explanation of homogeneous coordinates <br> - Example: `gl_Position` using `vec4(x, y, z, 1)` in homogeneous coordinates |
| **[Video 7](https://youtu.be/Cj6FBxf2dME?si=uY_H_8m1i9SJb-5b)** <br> Duration: 8:06 | - Explanation of `in` and `out` variables in vertex and fragment shaders <br> - Creation and linking of shaders using `glShaderSource`, `glCompileShader`, `glAttachShader`, `glLinkProgram`, `glDeleteShader`, `glUseProgram` <br> - Rendering a yellow triangle at the end |
| **[Video 8](https://youtu.be/lz5c1WpBiMg?si=DkZSGGgCGM9fsy68)** <br> Duration: 5:43 | - Coloring a triangle using a uniform variable <br> - Explanation and usage of glGetUniformLocation and glUniform functions|
| **[Video 9](https://youtu.be/cO5ZVmn6XPw?si=mpTmQDjMPh2u9x8I)** <br> Duration: 7:42 | - Rotating a triangle <br> - Working with the `glUniformMatrix4fv` function |
| **[Video 10](https://youtu.be/dCd29TxN7XM?si=A8zJLLzHRUIpdvB-)** <br> Duration: 7:11 | - Discussion of the stride concept <br> - Created a color buffer to color the triangle from previous videos |
| **[Video 11](https://youtu.be/M6IPySbbODk?si=fvo0J5cMV9UADLou)** <br> Duration: 7:41 | - Rotation of a triangle and a square on the same screen <br> - Positioning polygons using the `glm::translate` matrix from the GLM library |
| **[Video 12](https://youtu.be/CoQsSe83i3Y?si=dlPiiKfGrNdRekih)** <br> Duration: 5:28 | - Matrix multiplication and the transformation order from model to world coordinate <br> - Positioned 2 triangles and 2 squares, applying scale, rotation, and translation operations |
| **[Video 13](https://youtu.be/aKEyOv2JreA?si=KvsEmTkOqSw-OPDN)** <br> Duration: 4:09 | - Discussed Vertex Array Object (VAO) <br> - No longer need to save the triangle (and square) position VBO and color VBO globally <br> - Now saving the triangle (and square) VAO <br> - Covered the `glBindVertexArray` function |
| **[Video 14](https://youtu.be/fBftnaGB4ag?si=4318DQFLfEwB3_bl)** <br> Duration: 6:08 | - Element Buffer Object (EBO) <br> - Previously needed information of 2 triangles to render a square <br> - Now using an array of indices to connect and color the square <br> - Introduced another OpenGL object: `GL_ELEMENT_ARRAY_BUFFER` <br> - Covered the function `glDrawElements` |
| **[Video 15](https://youtu.be/HBKfZ1ADRzY?si=sYClMko6twaP0Sn8)** <br> Duration: 10:07 | - Created a unique buffer to retrieve information about square vertices' position, color, and indices <br> - Covered the function `glBufferSubData` |
| **[Video 16](https://youtu.be/o8Nb3HR4n9c?si=rbTWPRGfupiS0Dsb)** <br> Duration: 14:02 | - Drew a cube with a single buffer <br> - Approached world coordinates to projection coordinates using the `glm::perspective` matrix |
| **[Video 17](https://youtu.be/XBiL4UVPags?si=NezXssll9aogd3Ae)** <br> Duration: 5:50 | - Created a Shader Object <br> - Constructor used: `Shader(vertexFilePath, fragFilePath)` |
| **[Video 18](https://youtu.be/XAL-YM3MUFo?si=Oj82HcL_9SXEJP5D)** <br> Duration: 3:05 | - Finished the Shader class <br> - Implemented procedures to link the Shader |
| **[Video 19](https://youtu.be/pyFB9dszmn4?si=I37ttZaovIr4OPaV)** <br> Duration: 4:28 | - Discussed the `SendUniformData` function in the Shader class <br> - This function receives the variable name and data to send to the Shader <br> - Implemented using `unordered_map<string, int>` to represent the variable name and its location in the shader |


## How to Use This Playlist

1. **Start from the Beginning**: If you're new to OpenGL, it's recommended to start from the first video and work your way through the playlist sequentially. Each video builds on the previous ones, providing a comprehensive learning experience.
   
2. **Reference Individual Topics**: Already familiar with the basics? Feel free to jump to any video that covers a specific topic you're interested in.

3. **Practice**: OpenGL is best learned by doing. Try to implement the concepts discussed in each video by writing your own code and experimenting with different techniques.

## Link para o playlist no YouTube:
<div style="text-align: center;">
    <a href="https://youtube.com/playlist?list=PLVRDPs83ZhmfQGjLmOr6-m8VcPxjg_Jv0">
        <img src="https://img.youtube.com/vi/MqIg2InJTKM/default.jpg" alt="Link to video 01" width="250" />
    </a>
</div>

## Get Started

Ready to dive into graphical programming? [Watch the Playlist](https://www.youtube.com/playlist?list=PLVRDPs83ZhmfQGjLmOr6-m8VcPxjg_Jv0) on YouTube and start your journey with OpenGL!
