# Semana 1 - Deploy estatico (GitHub Pages)
## Links
- Repositorio: https://github.com/Lo-exe/nuvem-semana1-Lorenzo-Zottis-Vanzella
- Site (GitHub Pages): https://lo-exe.github.io/nuvem-semana1-Lorenzo-Zottis-Vanzella/
## O que foi feito
- Criei index.html, style.css e script.js pelo navegador
- Ativei GitHub Pages (main / root)
## Dificuldades
- (escreva 1-3 linhas)
# Semana 2 - GET/POST
## GET (clima)
{
  "fonte": "open-meteo.com",
  "temperatura": 23,
  "vento": 14.5,
  "unidade_temp": "°C",
  "unidade_vento": "km/h",
  "bruto": {
    "latitude": -24.375,
    "longitude": -53.875,
    "generationtime_ms": 0.04398822784423828,
    "utc_offset_seconds": 0,
    "timezone": "GMT",
    "timezone_abbreviation": "GMT",
    "elevation": 329,
    "current_units": {
      "time": "iso8601",
      "interval": "seconds",
      "temperature_2m": "°C",
      "wind_speed_10m": "km/h"
    },
    "current": {
      "time": "2026-03-02T11:15",
      "interval": 900,
      "temperature_2m": 23,
      "wind_speed_10m": 14.5
    }
  }
}
## POST 
{
  "fonte": "jsonplaceholder.typicode.com",
  "resposta": {
    "turma": "Serviços em Nuvem",
    "atividade": "Semana 2",
    "timestamp": "2026-03-02T11:22:34.150Z",
    "id": 101
  }
}
