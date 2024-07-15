---
title: Tables
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://erikflowers.github.io/weather-icons/css/weather-icons.css">
  <style>
    .weather {
      width: 20%;
      text-align: center;
      font-family: 'Times New Roman', Times, serif;
      font-size: 12px;
      background-color: rgb(240, 248, 255);
    }
    .weather th, .weather td {
      border: 1px solid #000;
      padding: 5px;
    }
    .weather thead {
      background-color: rgb(168, 218, 213);
    }
    .weather tr:hover {
      background-color: rgb(168, 218, 213);
    }
    .grades {
      text-align: center;
      min-width: 300px;
      width: 50%;
      margin: auto;
      margin-top: 50px;
      border-bottom: 1px solid #000;  
      border-top: 1px solid #000;
      border-collapse: collapse;
    }
    .grades tbody tr:nth-child(odd) {
      background-color: #f0f8ff;
    }
    .grades th, .grades td {
      padding: 5px;
    }
    .name {
      text-align: left;
    }
  </style>
  <title>Table Styles</title>
</head>
<body>
  <table class="weather">
    <thead>
      <tr>
        <th>Dia</th>
        <th>Tempo</th>
        <th>Mínima</th>
        <th>Máxima</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Domingo</td>
        <td><i class="wi wi-day-cloudy"></i></td> 
        <td>27°</td>
        <td>32°</td>
      </tr>
      <tr>
        <td>Segunda</td>
        <td><i class="wi wi-day-sunny"></i></td>
        <td>27°</td>
        <td>32°</td>
      </tr>
      <tr>
        <td>Terça</td>
        <td><i class="wi wi-day-rain"></i></td>
        <td>27°</td>
        <td>32°</td>
      </tr>
      <tr>
        <td>Quarta</td>
        <td><i class="wi wi-day-lightning"></i></td>
        <td>27°</td>
        <td>32°</td>
      </tr>
      <tr>
        <td>Quinta</td>
        <td><i class="wi wi-day-windy"></i></td>
        <td>27°</td>
        <td>32°</td>
      </tr>
      <tr>
        <td>Sexta</td>
        <td><i class="wi wi-cloudy"></i></td>
        <td>27°</td>
        <td>32°</td>
      </tr>
      <tr>
        <td>Sábado</td>
        <td><i class="wi wi-day-cloudy"></i></td>
        <td>27°</td>
        <td>32°</td>
      </tr>
    </tbody>
  </table>
  <table class="grades">
    <thead>
      <th></th>
      <th>Linguagem de Marcação</th>
      <th>Fundamentos da Computação</th>
      <th>Algoritmos</th>
    </thead>
    <tbody>
      <tr>
        <td class="name">Ada Lovelace</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>8.0</td>
      </tr>
      <tr>
        <td class="name">Ada Lovelace</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>8.0</td>
      </tr>
      <tr>
        <td class="name">Ada Lovelace</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>8.0</td>
      </tr>
      <tr>
        <td class="name">Ada Lovelace</td>
        <td>9.0</td>
        <td>10.0</td>
        <td>8.0</td>
      </tr>
    </tbody>
  </table>  
</body>
</html>