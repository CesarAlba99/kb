---
author: omaralba
title: JSON
date: 22-05-2025
tags: []
---

# JSON

## Java Script Object Notation

A lightweight data-interchange format, it´s easy for humans to read and write
and it´s easy for machines to parse and generate it.

Is built in two structures

### A collection of name/value pairs.

In some languages this is called an object, record, struct, hash, dictionary,
keyed list or associative array (this is good because is easy to parse and
manipulate in code)

### An ordered list of values

In some languages this is an array, vector, list or sequence. 


## Object 

An object is an unordered set of name/value pairs.An object begins with {  and
end with }. Each name is followed by : colon and the name/value pairs are
separated by , comma.

## Array

Is an ordered collection of values. An array begins with "["  and ends with "]"
Values are separated by , comma

## Value

Can be a string in double quotes, or a number, or true or false or null, or an
object or an array. These can be nested.

{
  "usuario": {
    "id": 123,
    "nombre": "Ana García",
    "activo": true
  },
  "proyectos": [
    {
      "id": 1,
      "nombre": "E-commerce",
      "tecnologias": ["React", "Node.js"]
    },
    {
      "id": 2,
      "nombre": "API REST",
      "tecnologias": ["Python", "FastAPI"]
    }
  ]
}
