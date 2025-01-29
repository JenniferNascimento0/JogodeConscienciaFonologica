# JogodeConscienciaFonologica
import pygame

from pygame.locals import *

from sys import exit

pygame.init()

#Definindo o tamanho da tela.

largura=640
            
altura=480

tela=pygame.display.set_mode((largura,altura))

#Nomeando o jogo.

pygame.display.set_caption("Jogo de Consiência Fonológica")


while True:

    for event in pygame.event.get():
    
        #Fechando a aba do jogo.
        
        if event.type == QUIT:
        
            pygame.quit()
            
            exit()
    
    pygame.display.update()
