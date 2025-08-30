# Weather McP Server

This project is a server that provides weather information using Model Context Protocol (MCP).

## Setup

1. Upload addictions:
`` `Bash
NPM INSTALL
`` `

2. Set Environment Variables:
`` `Bash
cp env.example .env
`` `

Add your OpenWeathermap API key by editing the `.env` file:
`` `
Weather_apı_base_url = https: //api.openweathermap.org/data/2.5/weather
Weather_apı_key = your_openweathermap_api_key_here
`` `

## Usage

Mix the 1st Project:
`` `Bash
NPM RUN Build
`` `

Start the 2nd Server:
`` `Bash
NPM Start
`` `

## Taking API key

To get the OpenWeathermap API key:
1. Go to https://openweathermap.org/
2. Create free account
Get your key from the 3rd API Keys section

## supported features

- `Get-Weather`: instant temperature information for the specified city
- Turkish language support
- Celsius Temperature Unit
