from ursina import *                app = Ursina() Sky() bird = Animation ('assets\img', collider='box', scale=(2,2,2), y=5) camera.orthographic = True camera.fov = 20 
 def update(): app.run()


