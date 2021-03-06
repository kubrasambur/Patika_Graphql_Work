# Patika_Graphql_work
 
## Features 
- User, Event, Location and Participant types have been created. 
- A User can have one or more Events.
- An Event has been related with a User.
- An Event has been related with a Location.
- An Event has been related with more than one Participant.
- Query to list all and fetch an id-based record on all types have been written.

## The following queries are working:
- query users{}
- query user(id: 1){}

- query events{}
- query event(id: 1){}
- query events{
  - id
  - title
  - user{
     id
      username
  - }
  - pariticipants{
      id
      username
  - }
  - location{
      id
      name
  - }
- }

- query locations{}
- query location(id: 1){}

- query participants{}
- query participant(id: 1){}

#
#
#

## Özellikler
- Temel olarak User, Event, Location ve Participant tipleri oluşturuldu. 
- Bir User'a ait bir veya birden fazla Event olabilir.
- Bir Event, bir User ile ilişkilidir.
- Bir Event, bir Location ile ilişkilidir.
- Bir Event birden fazla Participant ile ilişkilidir.
- Tüm tipler üzerinde tümünü listeleme ve id bazlı bir kaydı getirme Query'leri yazıldı.

## Aşağıdaki sorgular çalışır durumdadır:
- query users{}
- query user(id: 1){}

- query events{}
- query event(id: 1){}
- query events{
  - id
  - title
  - user{
     id
      username
  - }
  - pariticipants{
      id
      username
  - }
  - location{
      id
      name
  - }
- }

- query locations{}
- query location(id: 1){}

- query participants{}
- query participant(id: 1){}

## Installation
Clone this repository on your local machine.

```
git clone https://github.com/kubrasambur/Patika_Graphql_Work.git
```

## Usage
To use it after cloning the project:
```
cd Patika_Graphql_Work
cd .
```
Run the following commands in the project folder to install the project dependencies.

```
npm init
npm install
```
These instructions will get a copy of the project up and running on your local machine for development and testing purposes.

## To Run the Application
In the project directory you can run:

```
npm start
```
## For More Information
You can review the [Graphql](https://graphql.org/) documentation.
