# UE Streams Example: IEX Stock API Published to a Stream

To use this example you will need to do the following:

1. [Sign up for free with United Effects and register a platform for your Company](https://core.unitedeffects.com)
2. [Sign up for free with IEX so you can use their API to query market data](https://iexcloud.io/)

Once you've done the above, proceed as follows:

* Create a subject in UE Streams called "datalake.>"
* Create a stream in UE Streams called "datalake" and associate the subject from the first step
* Request publish access to the stream and make note of the values provided
* Copy .env.update to .env
* Update the data in .env from your publish access values

```
yarn && yarn dev
```
