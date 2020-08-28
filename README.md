# Momentum Clone

[Momentum](https://momentumdash.com/)이라는 Chrome addon의 시간표시 기능, 배경사진 표시 기능, 날씨 표시 기능을 따라해봤습니다.
배경사진은 [Unsplash](https://unsplash.com/) API를 사용하여 무작위로 받아오게 했고, 날씨는 [OpenWeatherMap](https://openweathermap.org/) API를 사용했습니다.

![Screenshot](./assets/Screenshot.png)

## 사용한 JavaScript feature

### Fetch API

- XHR 대비 개발자 친화적인 문법이 장점입니다.
- Promise를 사용하기 때문에 'Callback hell'을 피할 수 있습니다.
- async, await과 함께 사용하면 동기적(으로 보이는) 문법을 사용할 수 있어서 코드를 이해하기 쉬워집니다.
- 하지만, IE에서 지원하지 않는 등 [호환성 문제](https://caniuse.com/#search=fetch)가 있다는 단점이 있습니다.

## 개선할 수 있는 것들

1. [Geolocation API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API)를 이용하여 현재 위치의 날씨를 표시하기 (현재는 서울의 날씨만을 표시하고 있습니다.)
2. Unplash에서 사진을 받아오는 속도 개선? (지금은 1초 이상 걸리기도 함)
3. 변수 작명...
