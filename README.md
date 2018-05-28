Supervisord
=========

[![Travis-CI](https://travis-ci.org/deadc/deadcow.supervisord.svg?branch=master)](https://travis-ci.org/deadc/deadcow.supervisord)

Supervisor é um sistema que permite aos seus usuários monitorar e controlar uma série de processos em sistemas operacionais UNIX like.

Requerimentos
------------
Nenhum

Variaveis
--------------

Nenhum

Dependencias
------------

Nenhum

Playbook exemplo
----------------

    - hosts: all
    
      roles:
         - { role: supervisord }

Licença
-------

BSD

Author Information
------------------

Esta role foi desenvolvida por Thiago Freitas (deadcow@archlinux.com.br) em 03/2018
