![](https://lh5.googleusercontent.com/5Gr2dZXHJdmIiASsPw9put-6mR20e4g1gOk-af4krREaJ7NqkZnqXLD5QgiotfNHYhGRh387HSqdhjRwxdwOvQzg9ChhfIrZz0FdxVu6gktBtG-sy1MX6Xq36Gmrzu_6G_K7LDQZ)

Spearmint helps developers easily create functional React/Redux/Endpoint/Paint Timing tests without writing any code. It dynamically converts user inputs into executable Jest test code by using DOM query selectors provided by @testing-library.

## How to use

Download spearmint @ spearmintjs.com. Available for Mac OS and Windows.

To run React tests generated by spearmint, install the following in your dev dependencies.

    npm i -D jest @testing-library/jest-dom @testing-library/react test-data-bot

To run Redux tests generated by spearmint, install the following in your dev dependencies, in addition to your React test installations above.

    npm i -D redux-mock-store redux-thunk fetch-mock

To run Hooks / Context tests generated by spearmint, install the following in your dev dependencies, in addition to your React test installations above.

    npm i -D @testing-library/react-hooks

To run Endpoint tests generated by spearmint, install the following in your dev dependencies.

    npm i -D jest supertest

To run Puppeteer tests generated by spearmint, install the following in your dev dependencies.

    npm i -D jest puppeteer

## How it works

1.  On the initial screen, enter the URL of your project and load your application to start creating tests.

![](https://lh4.googleusercontent.com/CAFpoefRUUxgNosudQuc7gabSReFiI_puZ_WTjrzUSzB6pgOUdQ1babF2mxJql2lC8TQ-jjVLOgG5Qka8SUfF2fi-u2H9xSP7rZ_0Udpj-ISFPAY028UYKIUZcgOApnipVZwE7xh)

2.  Utilize our auto-complete, drop-down options, and tooltips features to easily create arrangement, action, and assertion test statements for React; reducer, action creator, asynchronous action creator, and middleware test statements for Redux; and hooks, context, and endpoint test statements.

![](/public/newReact.png?raw=true)

3.  Refer to the browser view of your app that is displayed on the right to quickly identify values for your selectors and use the file directory to open up a code editor view to easily refer to your codebase for props information.

4.  Spearmint will then convert user input to dynamically generate a test file that will be saved inside a **tests** folder, which you can use to run ‘npm test’ on.

![](/public/testfile.png?raw=true)

## Team

> Alex [@apark0720](https://github.com/apark0720) &nbsp;&middot;&nbsp;
> Charlie [@charlie-maloney](https://github.com/charlie-maloney) &nbsp;&middot;&nbsp;
> Chloe [@HeyItsChloe](https://github.com/HeyItsChloe) &nbsp;&middot;&nbsp;
> Cornelius [@corneeltron](https://github.com/corneeltron) &nbsp;&middot;&nbsp;
> Dave [@davefranz](https://github.com/davefranz) &nbsp;&middot;&nbsp;
> Johnny [@johnny-lim](https://github.com/johnny-lim) <br />
> Julie [@julicious100](https://github.com/julicious100) &nbsp;&middot;&nbsp;
> Karen [@karenpinilla](https://github.com/karenpinilla) &nbsp;&middot;&nbsp;
> Linda [@lcwish](https://github.com/lcwish) &nbsp;&middot;&nbsp;
> Mike [@mbcoker](https://github.com/mbcoker) &nbsp;&middot;&nbsp;
> Natlyn [@natlynp](https://github.com/natlynp) &nbsp;&middot;&nbsp;
> Rachel [@rachethecreator](https://github.com/rachethecreator) <br />
> Sieun [@sieunjang](https://github.com/sieunjang) &nbsp;&middot;&nbsp;
> Tristen [@twastell](https://github.com/twastell) &nbsp;&middot;&nbsp;
