#!/usr/bin/python
# -*- coding: utf-8 -*-


class SoftwareEngineer:

    def __init__(self):
        self.name = "Prashant Negi"
        self.role = "Full Stack Developer"
        self.language_spoken = ["Hindi", "English"]
        self.interests = ["WebDev.", "Java", "Python"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")


me = SoftwareEngineer()
me.say_hi()
