#!/usr/bin/python
# -*- coding: utf-8 -*-


class SoftwareEngineer:

    def __init__(self):
        self.name = "FeriVOQ"
        self.role = "Webfejlesztés"
        self.language_spoken = ["hun", "en"]

    def say_hi(self):
        print("Eyo.")


me = SoftwareEngineer()
me.say_hi()
