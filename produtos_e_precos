#!/usr/bin/env python
# -*- coding: utf-8 -*-
#
#  Lista de Preços.py
#  
#  Copyright 2021  <pi@suelizeuadrian>
#  
#  This program is free software; you can redistribute it and/or modify
#  it under the terms of the GNU General Public License as published by
#  the Free Software Foundation; either version 2 of the License, or
#  (at your option) any later version.
#  
#  This program is distributed in the hope that it will be useful,
#  but WITHOUT ANY WARRANTY; without even the implied warranty of
#  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#  GNU General Public License for more details.
#  
#  You should have received a copy of the GNU General Public License
#  along with this program; if not, write to the Free Software
#  Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston,
#  MA 02110-1301, USA.
#  
#  


import os

# INICIALIZA AS LISTAS COM VALORES ZERADOS
produtos = []
precos = []

os.system('clear')
print('{}{:^50}{}'.format('\033[7m','LISTA DE PRODUTOS','\033[m'))

print('''
Este aplicativo gera uma lista com nome dos produtos 
e seus preços e faz a somatória de todos o produtos  digitados...''')
while True:
    p = input('''
Digite o nome do produto ("x" se quiser finalizar): ''')
    if p == 'x' or p == 'X':
        break
    produtos.append(p)
    
    v = float(input('Valor do Produto: R$'))   
    precos.append(v)
    
os.system('clear')
print('{}{:^50}{}'.format('\033[7m','LISTA DE PRODUTOS','\033[m'))
count = 0
for i in produtos:
    
    
    print(f'{produtos[count]:.<40}R${precos[count]:,.2f}')
    count += 1

total =  sum(precos)
espaco = '''Preço total'''
print(f'\n{espaco:.<40}R${total:,.2f}')
