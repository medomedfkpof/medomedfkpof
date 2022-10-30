import ursina
from ursina import *
from ursina import curve
from ursina.prefabs.first_person_controller import FirstPersonController
salle_texture = 'assets/black-felt.png'

class Block( Button ):
    def __init__(self , position=(0 , 0 , 0) , texture='grass'):
        super().__init__(
            parent = scene ,
            position = position ,
            model = 'cube' ,
            scale = 1 ,
            texture = texture ,
            color = color.white ,
            origin_y = .5 ,
            highlight_color = color.lime ,
        )


class Block1( Button ):
    def __init__(self , position=(0 , 0 , 0)):
        super().__init__(
            parent = scene ,
            position = position ,
            model = 'cube' ,
            scale = 1 ,

            color = '#007CFF' ,
            origin_y = .5
        )

class Block2( Button ):
    def __init__(self , position=(0 , 0 , 0) , ):
        super().__init__(
            parent = scene ,
            position = position ,
            model = 'cube' ,
            scale = 1 ,

            color = '#000000' ,
            origin_y = .5 ,
            highlight_color = color.lime ,
        )


class Hand( ursina.Entity ):
    def __init__(self):
        super().__init__(
            parent = ursina.camera.ui,
            model = 'cube',
            scale = (0.2,0.3),
            color = ursina.color.white,
            rotation=ursina.Vec3( 150 , -10 , 0 ),
            position=ursina.Vec2( 0.4 , -0.4 )
           )


app = Ursina()
player = FirstPersonController( position = (27 , 50 , 27))
player.enabled = False
sky = Sky()
hand = Hand()
window.fullscreen = True


ballon = Entity(
    model = 'sphere',
    color = '#000000',
    parent = ursina.camera.ui  ,
    scale = (0.2 , 0.3) ,

    rotation = ursina.Vec3( 150 , -10 , 0 ) ,
    position = ursina.Vec2( 0.4 , -0.4 )

)
class cage():

        utton_8551 = Block2(


            position = (25 , 50 , 40))
        utton_8551 =  Block2(


             position = (25 , 51 , 40))
        utton_8551 =  Block2(


            position = (25 , 52 , 40))
        utton_8551 = Block2(


            position = (25 , 53 , 40))

        utton_8551 = Block2(


            position = (25 , 54 , 40))
        utton_8551 = Block2(

            position = (26 , 54 , 40)
        )
        utton_8551 = Block2(

            position = (27 , 54 , 40)
        )
        utton_8551 = Block2(

            position = (28 , 54 , 40)
        )
        utton_8551 =  Block2(


           position = (29 , 53 , 40))
        utton_8551 = Block2(

            position = (29 , 54 , 40)
        )
        utton_8551 =  Block2(


           position = (29 , 52 , 40))
        utton_8551 =  Block2(


            position = (29 , 51 , 40))
        utton_8551 =  Block2(


            position = (29 , 50 , 40))
        utton_8551 = Block1(


            position = (29 , 50 , 41))
        utton_8551 = Block1(


            position = (29 , 50 , 42))
        utton_8551 =Block1(


            position = (29 , 51 , 42))
        utton_8551 =Block1(


            position = (29 , 52 , 42))
        utton_8551 = Block1(

            position = (29 , 54 , 42))
        utton_8551 = Block1(

            position = (29 , 54 , 41)
        )
        utton_8551 = Block1(

            position = (25 , 54 , 41))
        utton_8551 = Block1(

            position = (26 , 54 , 41))
        utton_8551 = Block1(

            position = (27 , 54 , 41)
        )
        utton_8551 = Block1(

            position = (28 , 54 , 41))
        utton_8551 = Block1(

            position = (28 , 54 , 42))
        utton_8551 = Block1(

            position = (27 , 54 , 42))
        utton_8551 = Block1(

            position = (26 , 54, 42))
        utton_8551 = Block1(

            position = (25 , 54 , 42)
        )

        utton_8551 = Block1(


            position = (28 , 50 , 42))
        utton_8551 = Block1(

            position = (28 , 51 , 42))
        utton_8551 = Block1(


            position = (28 , 52 , 42))
        utton_8551 = Block1(


            position = (27 , 50 , 42))
        utton_8551 = Block1(


            position = (27 , 51 , 42))
        utton_8551 = Block1(


            position = (27 , 52 , 42))
        utton_8551 = Block1(


            position = (26 , 50 , 42))
        utton_8551 = Block1(

            position = (26 , 51 , 42)
        )
        utton_8551 = Block1(

            position = (26 , 52 , 42)
        )
        utton_8551 = Block1(

            position = (25 , 50 , 42)
        )
        utton_8551 = Block1(

            position = (25 , 51 , 42)
        )
        utton_8551 = Block1(

            position = (25 , 52 , 42)
        )
        utton_8551 = Block1(

            position = (25 , 53 , 42)
        )
        utton_8551 = Block1(

            position = (26 , 53 , 42)
        )
        utton_8551 = Block1(

            position = (27 , 53 , 42)
        )
        utton_8551 = Block1(

            position = (28 , 53 , 42)
        )
        utton_8551 = Block1(

            position = (29 , 53 , 42)
        )
        utton_8551 = Block1(

            position = (29 , 53 , 41)
        )
        utton_8551 = Block1(

            position = (29 , 52 , 41)
        )
        utton_8551 = Block1(

            position = (29 , 51 , 41)
        )
        utton_8551 = Block1(

            position = (29 , 50 , 41)
        )
        utton_8551 = Block1(

            position = (25 , 53 , 41)
        )
        utton_8551 = Block1(

            position = (25 , 52 , 41)
        )
        utton_8551 = Block1(

            position = (25 , 51 , 41)
        )
        utton_8551 = Block1(

            position = (25 , 50 , 41)
        )





cage = cage()
def input(key):
    if key=='escape':
        quit()

#def input(self, key ):
      #if sehoveredlf.:
       # if key == 'left mouse down':


for z in range( 50 ):
    for x in range( 50 ):
        block = Block( position = (x , 50 , z) )
def spin():
    ballon.animate('rotation_y', ballon.rotation_y+360, duration=2, curve=curve.in_out_expo)

mouse.visible = False



app.run()

