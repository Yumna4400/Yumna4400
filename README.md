
import random
import time

class Car:
    def __init__(self, x, y):
        self.x = x
        self.y = y
        self.speed = 0

    def move(self, direction, speed):
        if direction == "forward":
            self.y += speed
        elif direction == "backward":
            self.y -= speed
        elif direction == "left":
            self.x -= speed
        elif direction
