# Comandos XAMPP

## 1. Iniciar base de datos
mysql -h localhost -u root -p

## 2. Crear base de datos
create database **demo**;

## 3. Ver bases de datos
show databases;

## 4. Editar base de datos
use **demo**;

### Crear tabla
create table **cliente**(
    -> *codigo_cliente*
    -> *nombre*
    -> );

### Ver tablas
show tables;

#### Mostrar tabla
Describe **cliente**;
