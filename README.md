# Malaysia Map Data

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fjerrychong25%2Fmalaysia-map-data&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/jerrychong25)

## Introduction

This repo stores Malaysia map data retrieved from [OpenStreetMap](https://www.openstreetmap.org/).

## Authors

**Jerry Chong** - [jerrychong25](https://github.com/jerrychong25)

## Overpass API

### Public Transport

Putrajaya Bus Stop - https://overpass-api.de/api/interpreter?data=%2F*%0AThis%20has%20been%20generated%20by%20the%20overpass-turbo%20wizard.%0A*%2F%0A%5Bout%3Ajson%5D%5Btimeout%3A25%5D%3B%0A%2F%2F%20fetch%20area%20%E2%80%9CPutrajaya%E2%80%9D%20to%20search%20in%0Aarea%28id%3A3604443881%29-%3E.putrajaya%3B%0A%2F%2F%20gather%20results%0A%28%0A%20%20node%5Bhighway~%22bus_stop%22%5D%28area.putrajaya%29%3B%0A%20%20way%5Bhighway~%22bus_stop%22%5D%28area.putrajaya%29%3B%0A%20%20relation%5Bhighway~%22bus_stop%22%5D%28area.putrajaya%29%3B%0A%29%3B%0A%2F%2F%20print%20results%0Aout%20body%3B%0A%3E%3B%0Aout%20skel%20qt%3B

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
