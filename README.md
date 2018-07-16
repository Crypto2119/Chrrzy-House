# Chrrzy-House
import simplegui

def draw_handler(canvas):
    canvas.draw_polygon([(400, 100), (500, 300), (300, 300)], 12, 'Black', 'Red')
    canvas.draw_polygon([(300, 300), (500, 300), (500, 500), (300, 500)], 12, 'Black', 'Black')

frame = simplegui.create_frame('Cheezy House', 900, 900)

frame.set_canvas_background("Blue")
frame.set_draw_handler(draw_handler)
frame.start()
