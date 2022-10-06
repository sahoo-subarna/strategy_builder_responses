# strategy_builder_responses
#### Underlying Price at : 17331.8

## BELOW (17331.8 < 17400)
>{
>
>    "symbol":"NIFTY",
>    "token": 26000,
>    "prediction":"BELOW",
>    "expiryDate":"20221013",
>    "instrumentPriceRange":[
>        17400
>    ]
>}




```
{
  "data": {
    "tradingOpportunities": [
      {
        "strategyName": "Bear Call Spread",
        "legs": [
          {
            "option": {
              "token": 52956,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17350,
              "optionType": "CE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317350CE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 138.8,
              "greeks": {
                "theta": -10.593092951259933,
                "delta": 0.4846549379763911,
                "gamma": 0.001077145520826698,
                "vega": 9.543571464547176,
                "iv": 15.459376096259803
              }
            },
            "action": "SELL",
            "quantity": 50
          },
          {
            "option": {
              "token": 52958,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17400,
              "optionType": "CE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317400CE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 114.3,
              "greeks": {
                "theta": -10.292359480501776,
                "delta": 0.4301508205989048,
                "gamma": 0.0010764004427733435,
                "vega": 9.403873004984497,
                "iv": 15.24362654890865
              }
            },
            "action": "BUY",
            "quantity": 50
          }
        ],
        "maxLoss": 1274.9999999999993,
        "maxProfit": 1225.0000000000007,
        "isInfiniteProfit": false,
        "isInfiniteLoss": false,
        "breakEven": [17374.5]
      },
      {
        "strategyName": "Bear Put Spread",
        "legs": [
          {
            "option": {
              "token": 52957,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17350,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317350PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 166.75,
              "greeks": {
                "theta": -10.593092951259933,
                "delta": 0.5153450620236089,
                "gamma": 0.001077145520826698,
                "vega": 9.543571464547176,
                "iv": 15.459376096259803
              }
            },
            "action": "BUY",
            "quantity": 50
          },
          {
            "option": {
              "token": 52955,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17300,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317300PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 144.75,
              "greeks": {
                "theta": -10.670554961984253,
                "delta": 0.4618213174876212,
                "gamma": 0.001061117218620536,
                "vega": 9.506869511726546,
                "iv": 15.632541268132627
              }
            },
            "action": "SELL",
            "quantity": 50
          }
        ],
        "maxLoss": 1100,
        "maxProfit": -1050,
        "isInfiniteProfit": false,
        "isInfiniteLoss": false,
        "breakEven": [17328]
      },
      {
        "strategyName": "Bear Put Spread",
        "legs": [
          {
            "option": {
              "token": 52957,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17350,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317350PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 166.75,
              "greeks": {
                "theta": -10.593092951259933,
                "delta": 0.5153450620236089,
                "gamma": 0.001077145520826698,
                "vega": 9.543571464547176,
                "iv": 15.459376096259803
              }
            },
            "action": "BUY",
            "quantity": 50
          },
          {
            "option": {
              "token": 52951,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17250,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317250PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 124.45,
              "greeks": {
                "theta": -10.499854217638378,
                "delta": 0.4095283285275388,
                "gamma": 0.001032832594195659,
                "vega": 9.303983908682163,
                "iv": 15.71789663285017
              }
            },
            "action": "SELL",
            "quantity": 50
          }
        ],
        "maxLoss": 2115,
        "maxProfit": -2014.9999999999998,
        "isInfiniteProfit": false,
        "isInfiniteLoss": false,
        "breakEven": [17307.7]
      },
      {
        "strategyName": "Bear Put Spread",
        "legs": [
          {
            "option": {
              "token": 52957,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17350,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317350PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 166.75,
              "greeks": {
                "theta": -10.593092951259933,
                "delta": 0.5153450620236089,
                "gamma": 0.001077145520826698,
                "vega": 9.543571464547176,
                "iv": 15.459376096259803
              }
            },
            "action": "BUY",
            "quantity": 50
          },
          {
            "option": {
              "token": 52949,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17200,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317200PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 106,
              "greeks": {
                "theta": -10.218532046599156,
                "delta": 0.35989941651129154,
                "gamma": 0.0009832503120145877,
                "vega": 8.955475509721587,
                "iv": 15.89205174241215
              }
            },
            "action": "SELL",
            "quantity": 50
          }
        ],
        "maxLoss": 3037.5,
        "maxProfit": -2887.5,
        "isInfiniteProfit": false,
        "isInfiniteLoss": false,
        "breakEven": [17289.25]
      },
      {
        "strategyName": "Bear Put Spread",
        "legs": [
          {
            "option": {
              "token": 52957,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17350,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317350PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 166.75,
              "greeks": {
                "theta": -10.593092951259933,
                "delta": 0.5153450620236089,
                "gamma": 0.001077145520826698,
                "vega": 9.543571464547176,
                "iv": 15.459376096259803
              }
            },
            "action": "BUY",
            "quantity": 50
          },
          {
            "option": {
              "token": 52945,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17150,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317150PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 89.25,
              "greeks": {
                "theta": -9.749167921754063,
                "delta": 0.3128482825354067,
                "gamma": 0.0009239226746655702,
                "vega": 8.479376842148278,
                "iv": 16.013406333513558
              }
            },
            "action": "SELL",
            "quantity": 50
          }
        ],
        "maxLoss": 3875,
        "maxProfit": -3675,
        "isInfiniteProfit": false,
        "isInfiniteLoss": false,
        "breakEven": [17272.5]
      },
      {
        "strategyName": "Ratio Put Spread",
        "legs": [
          {
            "option": {
              "token": 52957,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17350,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317350PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 166.75,
              "greeks": {
                "theta": -10.593092951259933,
                "delta": 0.5153450620236089,
                "gamma": 0.001077145520826698,
                "vega": 9.543571464547176,
                "iv": 15.459376096259803
              }
            },
            "action": "BUY",
            "quantity": 50
          },
          {
            "option": {
              "token": 52955,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17300,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317300PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 144.75,
              "greeks": {
                "theta": -10.670554961984253,
                "delta": 0.4618213174876212,
                "gamma": 0.001061117218620536,
                "vega": 9.506869511726546,
                "iv": 15.632541268132627
              }
            },
            "action": "SELL",
            "quantity": 100
          }
        ],
        "maxLoss": 0,
        "maxProfit": -20312.5,
        "isInfiniteProfit": false,
        "isInfiniteLoss": true,
        "breakEven": [17706.25]
      },
      {
        "strategyName": "Ratio Put Spread",
        "legs": [
          {
            "option": {
              "token": 52957,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17350,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317350PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 166.75,
              "greeks": {
                "theta": -10.593092951259933,
                "delta": 0.5153450620236089,
                "gamma": 0.001077145520826698,
                "vega": 9.543571464547176,
                "iv": 15.459376096259803
              }
            },
            "action": "BUY",
            "quantity": 50
          },
          {
            "option": {
              "token": 52951,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17250,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317250PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 124.45,
              "greeks": {
                "theta": -10.499854217638378,
                "delta": 0.4095283285275388,
                "gamma": 0.001032832594195659,
                "vega": 9.303983908682163,
                "iv": 15.71789663285017
              }
            },
            "action": "SELL",
            "quantity": 100
          }
        ],
        "maxLoss": 0,
        "maxProfit": -15782.499999999998,
        "isInfiniteProfit": false,
        "isInfiniteLoss": true,
        "breakEven": [17565.65]
      },
      {
        "strategyName": "Ratio Put Spread",
        "legs": [
          {
            "option": {
              "token": 52957,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17350,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317350PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 166.75,
              "greeks": {
                "theta": -10.593092951259933,
                "delta": 0.5153450620236089,
                "gamma": 0.001077145520826698,
                "vega": 9.543571464547176,
                "iv": 15.459376096259803
              }
            },
            "action": "BUY",
            "quantity": 50
          },
          {
            "option": {
              "token": 52949,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17200,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317200PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 106,
              "greeks": {
                "theta": -10.218532046599156,
                "delta": 0.35989941651129154,
                "gamma": 0.0009832503120145877,
                "vega": 8.955475509721587,
                "iv": 15.89205174241215
              }
            },
            "action": "SELL",
            "quantity": 100
          }
        ],
        "maxLoss": 0,
        "maxProfit": -11437.5,
        "isInfiniteProfit": false,
        "isInfiniteLoss": true,
        "breakEven": [17428.75]
      },
      {
        "strategyName": "Ratio Put Spread",
        "legs": [
          {
            "option": {
              "token": 52957,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17350,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317350PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 166.75,
              "greeks": {
                "theta": -10.593092951259933,
                "delta": 0.5153450620236089,
                "gamma": 0.001077145520826698,
                "vega": 9.543571464547176,
                "iv": 15.459376096259803
              }
            },
            "action": "BUY",
            "quantity": 50
          },
          {
            "option": {
              "token": 52945,
              "instrumentName": "OPTIDX",
              "symbol": "NIFTY",
              "strikePrice": 17150,
              "optionType": "PE",
              "lotSize": 50,
              "securityDesc": "NIFTY22O1317150PE",
              "marketSegmentId": 2,
              "expYYYYMMDD": "20221013",
              "ltp": 89.25,
              "greeks": {
                "theta": -9.749167921754063,
                "delta": 0.3128482825354067,
                "gamma": 0.0009239226746655702,
                "vega": 8.479376842148278,
                "iv": 16.013406333513558
              }
            },
            "action": "SELL",
            "quantity": 100
          }
        ],
        "maxLoss": 0,
        "maxProfit": -7262.5,
        "isInfiniteProfit": false,
        "isInfiniteLoss": true,
        "breakEven": [17295.25]
      }
    ],
    "underlyingPrice": 17331.8
  },
  "message": "-",
  "status": "success"
}
```


## BELOW (17331.8 > 17200)
>{
>
>    "symbol":"NIFTY",
>    "token": 26000,
>    "prediction":"BELOW",
>    "expiryDate":"20221013",
>    "instrumentPriceRange":[
>        17200
>    ]
>}

```
{
    "data": {
        "tradingOpportunities": [
            {
                "strategyName": "Bear Put Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52957,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 166.75,
                            "greeks": {
                                "theta": -10.599498241008313,
                                "delta": 0.5153450619493934,
                                "gamma": 0.0010771455174825994,
                                "vega": 9.540687447768933,
                                "iv": 15.46404929831624
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52949,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17200,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317200PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 106,
                            "greeks": {
                                "theta": -10.224710771320574,
                                "delta": 0.3598994159763687,
                                "gamma": 0.0009832503156851228,
                                "vega": 8.952769207771235,
                                "iv": 15.896855620667338
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 3037.5,
                "maxProfit": -2887.5,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17289.25
                ]
            },
            {
                "strategyName": "Bear Put Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52957,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 166.75,
                            "greeks": {
                                "theta": -10.599498241008313,
                                "delta": 0.5153450619493934,
                                "gamma": 0.0010771455174825994,
                                "vega": 9.540687447768933,
                                "iv": 15.46404929831624
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52945,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17150,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317150PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 89.25,
                            "greeks": {
                                "theta": -9.755062914639346,
                                "delta": 0.3128482829054957,
                                "gamma": 0.0009239226730633876,
                                "vega": 8.47681442361144,
                                "iv": 16.018246999010444
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 3875,
                "maxProfit": -3675,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17272.5
                ]
            },
            {
                "strategyName": "Bear Put Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52957,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 166.75,
                            "greeks": {
                                "theta": -10.599498241008313,
                                "delta": 0.5153450619493934,
                                "gamma": 0.0010771455174825994,
                                "vega": 9.540687447768933,
                                "iv": 15.46404929831624
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52935,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17100,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317100PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 75.8,
                            "greeks": {
                                "theta": -9.075371683248648,
                                "delta": 0.26782297340587924,
                                "gamma": 0.0008584452843753899,
                                "vega": 7.881127359890723,
                                "iv": 16.0285288002342
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 4547.5,
                "maxProfit": -4297.5,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17259.05
                ]
            },
            {
                "strategyName": "Bear Put Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52957,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 166.75,
                            "greeks": {
                                "theta": -10.599498241008313,
                                "delta": 0.5153450619493934,
                                "gamma": 0.0010771455174825994,
                                "vega": 9.540687447768933,
                                "iv": 15.46404929831624
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52933,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17050,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317050PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 63.4,
                            "greeks": {
                                "theta": -8.364452111775892,
                                "delta": 0.22740613742268578,
                                "gamma": 0.0007819060856536955,
                                "vega": 7.220975508863611,
                                "iv": 16.123495995998383
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 5167.5,
                "maxProfit": -4867.5,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17246.65
                ]
            },
            {
                "strategyName": "Ratio Put Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52957,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 166.75,
                            "greeks": {
                                "theta": -10.599498241008313,
                                "delta": 0.5153450619493934,
                                "gamma": 0.0010771455174825994,
                                "vega": 9.540687447768933,
                                "iv": 15.46404929831624
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52949,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17200,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317200PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 106,
                            "greeks": {
                                "theta": -10.224710771320574,
                                "delta": 0.3598994159763687,
                                "gamma": 0.0009832503156851228,
                                "vega": 8.952769207771235,
                                "iv": 15.896855620667338
                            }
                        },
                        "action": "SELL",
                        "quantity": 100
                    }
                ],
                "maxLoss": 0,
                "maxProfit": -11437.5,
                "isInfiniteProfit": false,
                "isInfiniteLoss": true,
                "breakEven": [
                    17428.75
                ]
            },
            {
                "strategyName": "Ratio Put Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52957,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 166.75,
                            "greeks": {
                                "theta": -10.599498241008313,
                                "delta": 0.5153450619493934,
                                "gamma": 0.0010771455174825994,
                                "vega": 9.540687447768933,
                                "iv": 15.46404929831624
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52945,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17150,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317150PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 89.25,
                            "greeks": {
                                "theta": -9.755062914639346,
                                "delta": 0.3128482829054957,
                                "gamma": 0.0009239226730633876,
                                "vega": 8.47681442361144,
                                "iv": 16.018246999010444
                            }
                        },
                        "action": "SELL",
                        "quantity": 100
                    }
                ],
                "maxLoss": 0,
                "maxProfit": -7262.5,
                "isInfiniteProfit": false,
                "isInfiniteLoss": true,
                "breakEven": [
                    17295.25
                ]
            },
            {
                "strategyName": "Ratio Put Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52957,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 166.75,
                            "greeks": {
                                "theta": -10.599498241008313,
                                "delta": 0.5153450619493934,
                                "gamma": 0.0010771455174825994,
                                "vega": 9.540687447768933,
                                "iv": 15.46404929831624
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52935,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17100,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317100PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 75.8,
                            "greeks": {
                                "theta": -9.075371683248648,
                                "delta": 0.26782297340587924,
                                "gamma": 0.0008584452843753899,
                                "vega": 7.881127359890723,
                                "iv": 16.0285288002342
                            }
                        },
                        "action": "SELL",
                        "quantity": 100
                    }
                ],
                "maxLoss": 0,
                "maxProfit": -3417.4999999999995,
                "isInfiniteProfit": false,
                "isInfiniteLoss": true,
                "breakEven": [
                    17168.35
                ]
            },
            {
                "strategyName": "Ratio Put Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52957,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 166.75,
                            "greeks": {
                                "theta": -10.599498241008313,
                                "delta": 0.5153450619493934,
                                "gamma": 0.0010771455174825994,
                                "vega": 9.540687447768933,
                                "iv": 15.46404929831624
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52933,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17050,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317050PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 63.4,
                            "greeks": {
                                "theta": -8.364452111775892,
                                "delta": 0.22740613742268578,
                                "gamma": 0.0007819060856536955,
                                "vega": 7.220975508863611,
                                "iv": 16.123495995998383
                            }
                        },
                        "action": "SELL",
                        "quantity": 100
                    }
                ],
                "maxLoss": 0,
                "maxProfit": 322.5000000000001,
                "isInfiniteProfit": false,
                "isInfiniteLoss": true,
                "breakEven": [
                    17043.55
                ]
            }
        ],
        "underlyingPrice": 17331.8
    },
    "message": "-",
    "status": "success"
}
```


## ABOVE (17331.8 < 17400)
>{
>
>    "symbol":"NIFTY",
>    "token": 26000,
>    "prediction":"ABOVE",
>    "expiryDate":"20221013",
>    "instrumentPriceRange":[
>        17400
>    ]
>}

{
    "data": {
        "tradingOpportunities": [
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.60578233999985,
                                "delta": 0.48465493805073195,
                                "gamma": 0.0010771455174769496,
                                "vega": 9.537860522532938,
                                "iv": 15.468632685951889
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52958,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17400,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317400CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 114.3,
                            "greeks": {
                                "theta": -10.304688557339198,
                                "delta": 0.43015082035731483,
                                "gamma": 0.0010764004460165407,
                                "vega": 9.398245658451597,
                                "iv": 15.252753859385848
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 1225.0000000000007,
                "maxProfit": 1274.9999999999993,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17374.5
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.60578233999985,
                                "delta": 0.48465493805073195,
                                "gamma": 0.0010771455174769496,
                                "vega": 9.537860522532938,
                                "iv": 15.468632685951889
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52972,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17450,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317450CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 92.8,
                            "greeks": {
                                "theta": -9.830419512076414,
                                "delta": 0.37582292852405497,
                                "gamma": 0.0010529116005331962,
                                "vega": 9.07871544417407,
                                "iv": 15.06287360098213
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 2300.000000000001,
                "maxProfit": 2699.999999999999,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17396
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.60578233999985,
                                "delta": 0.48465493805073195,
                                "gamma": 0.0010771455174769496,
                                "vega": 9.537860522532938,
                                "iv": 15.468632685951889
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52978,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17500,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317500CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 73.35,
                            "greeks": {
                                "theta": -9.118803210972537,
                                "delta": 0.3217668044029578,
                                "gamma": 0.0010127861520373871,
                                "vega": 8.575712679818771,
                                "iv": 14.792030910030007
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 3272.500000000001,
                "maxProfit": 4227.499999999999,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17415.45
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.60578233999985,
                                "delta": 0.48465493805073195,
                                "gamma": 0.0010771455174769496,
                                "vega": 9.537860522532938,
                                "iv": 15.468632685951889
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52982,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17550,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317550CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 57.15,
                            "greeks": {
                                "theta": -8.297371280100176,
                                "delta": 0.27041338964670253,
                                "gamma": 0.0009486131283747868,
                                "vega": 7.916938117182232,
                                "iv": 14.579527778550982
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 4082.5000000000005,
                "maxProfit": 5917.5,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17431.65
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.60578233999985,
                                "delta": 0.48465493805073195,
                                "gamma": 0.0010771455174769496,
                                "vega": 9.537860522532938,
                                "iv": 15.468632685951889
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52958,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17400,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317400CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 114.3,
                            "greeks": {
                                "theta": -10.304688557339198,
                                "delta": 0.43015082035731483,
                                "gamma": 0.0010764004460165407,
                                "vega": 9.398245658451597,
                                "iv": 15.252753859385848
                            }
                        },
                        "action": "SELL",
                        "quantity": 100
                    }
                ],
                "maxLoss": 0,
                "maxProfit": 6989.999999999999,
                "isInfiniteProfit": false,
                "isInfiniteLoss": true,
                "breakEven": [
                    17539.8
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.60578233999985,
                                "delta": 0.48465493805073195,
                                "gamma": 0.0010771455174769496,
                                "vega": 9.537860522532938,
                                "iv": 15.468632685951889
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52972,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17450,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317450CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 92.8,
                            "greeks": {
                                "theta": -9.830419512076414,
                                "delta": 0.37582292852405497,
                                "gamma": 0.0010529116005331962,
                                "vega": 9.07871544417407,
                                "iv": 15.06287360098213
                            }
                        },
                        "action": "SELL",
                        "quantity": 100
                    }
                ],
                "maxLoss": 0,
                "maxProfit": 7339.999999999999,
                "isInfiniteProfit": false,
                "isInfiniteLoss": true,
                "breakEven": [
                    17596.8
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.60578233999985,
                                "delta": 0.48465493805073195,
                                "gamma": 0.0010771455174769496,
                                "vega": 9.537860522532938,
                                "iv": 15.468632685951889
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52978,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17500,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317500CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 73.35,
                            "greeks": {
                                "theta": -9.118803210972537,
                                "delta": 0.3217668044029578,
                                "gamma": 0.0010127861520373871,
                                "vega": 8.575712679818771,
                                "iv": 14.792030910030007
                            }
                        },
                        "action": "SELL",
                        "quantity": 100
                    }
                ],
                "maxLoss": 0,
                "maxProfit": 7894.999999999999,
                "isInfiniteProfit": false,
                "isInfiniteLoss": true,
                "breakEven": [
                    17657.9
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.60578233999985,
                                "delta": 0.48465493805073195,
                                "gamma": 0.0010771455174769496,
                                "vega": 9.537860522532938,
                                "iv": 15.468632685951889
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52982,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17550,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317550CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 57.15,
                            "greeks": {
                                "theta": -8.297371280100176,
                                "delta": 0.27041338964670253,
                                "gamma": 0.0009486131283747868,
                                "vega": 7.916938117182232,
                                "iv": 14.579527778550982
                            }
                        },
                        "action": "SELL",
                        "quantity": 100
                    }
                ],
                "maxLoss": 0,
                "maxProfit": 8775,
                "isInfiniteProfit": false,
                "isInfiniteLoss": true,
                "breakEven": [
                    17725.5
                ]
            }
        ],
        "underlyingPrice": 17331.8
    },
    "message": "-",
    "status": "success"
}
```



## ABOVE (17331.8 > 17200)
>{
>
>    "symbol":"NIFTY",
>    "token": 26000,
>    "prediction":"ABOVE",
>    "expiryDate":"20221013",
>    "instrumentPriceRange":[
>        17200
>    ]
>}

```
{
    "data": {
        "tradingOpportunities": [
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.608323288978811,
                                "delta": 0.4846549379837184,
                                "gamma": 0.0010771455204965344,
                                "vega": 9.53671816695399,
                                "iv": 15.470485552214086
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52958,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17400,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317400CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 114.3,
                            "greeks": {
                                "theta": -10.307157378836926,
                                "delta": 0.4301508202120405,
                                "gamma": 0.0010764004479667598,
                                "vega": 9.39712002408225,
                                "iv": 15.2545808814466
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 1225.0000000000007,
                "maxProfit": 1274.9999999999993,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17374.5
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.608323288978811,
                                "delta": 0.4846549379837184,
                                "gamma": 0.0010771455204965344,
                                "vega": 9.53671816695399,
                                "iv": 15.470485552214086
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52972,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17450,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317450CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 92.8,
                            "greeks": {
                                "theta": -9.83277473714427,
                                "delta": 0.37582292865303335,
                                "gamma": 0.001052911599585305,
                                "vega": 9.077628081726338,
                                "iv": 15.064677922055125
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 2300.000000000001,
                "maxProfit": 2699.999999999999,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17396
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.608323288978811,
                                "delta": 0.4846549379837184,
                                "gamma": 0.0010771455204965344,
                                "vega": 9.53671816695399,
                                "iv": 15.470485552214086
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52978,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17500,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317500CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 73.35,
                            "greeks": {
                                "theta": -9.120987916533148,
                                "delta": 0.3217668041476536,
                                "gamma": 0.0010127861531965417,
                                "vega": 8.574685558523738,
                                "iv": 14.793802751228213
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 3272.500000000001,
                "maxProfit": 4227.499999999999,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17415.45
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.608323288978811,
                                "delta": 0.4846549379837184,
                                "gamma": 0.0010771455204965344,
                                "vega": 9.53671816695399,
                                "iv": 15.470485552214086
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52982,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17550,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317550CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 57.15,
                            "greeks": {
                                "theta": -8.299359242797577,
                                "delta": 0.270413390425581,
                                "gamma": 0.0009486131262055663,
                                "vega": 7.915989911949939,
                                "iv": 14.58127424120903
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 4082.5000000000005,
                "maxProfit": 5917.5,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17431.65
                ]
            },
            {
                "strategyName": "Bull Put Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52955,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17300,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317300PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 144.75,
                            "greeks": {
                                "theta": -10.685896676808285,
                                "delta": 0.4618213175109778,
                                "gamma": 0.001061117217786012,
                                "vega": 9.500042570079124,
                                "iv": 15.643775172065943
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52971,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17400,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317400PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 191.85,
                            "greeks": {
                                "theta": -10.307157378836926,
                                "delta": 0.5698491797879596,
                                "gamma": 0.0010764004479667598,
                                "vega": 9.39712002408225,
                                "iv": 15.2545808814466
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 2645.0000000000005,
                "maxProfit": 2354.9999999999995,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17352.9
                ]
            },
            {
                "strategyName": "Bull Put Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52955,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17300,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317300PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 144.75,
                            "greeks": {
                                "theta": -10.685896676808285,
                                "delta": 0.4618213175109778,
                                "gamma": 0.001061117217786012,
                                "vega": 9.500042570079124,
                                "iv": 15.643775172065943
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52977,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17450,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317450PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 221.2,
                            "greeks": {
                                "theta": -9.83277473714427,
                                "delta": 0.6241770713469666,
                                "gamma": 0.001052911599585305,
                                "vega": 9.077628081726338,
                                "iv": 15.064677922055125
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 3677.5000000000005,
                "maxProfit": 3822.4999999999995,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17373.55
                ]
            },
            {
                "strategyName": "Bull Put Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52951,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17250,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317250PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 124.45,
                            "greeks": {
                                "theta": -10.514950514595519,
                                "delta": 0.40952832865545397,
                                "gamma": 0.0010328325926315686,
                                "vega": 9.297302661085562,
                                "iv": 15.72919188765809
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52971,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17400,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317400PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 191.85,
                            "greeks": {
                                "theta": -10.307157378836926,
                                "delta": 0.5698491797879596,
                                "gamma": 0.0010764004479667598,
                                "vega": 9.39712002408225,
                                "iv": 15.2545808814466
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 4130,
                "maxProfit": 3369.9999999999995,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17332.6
                ]
            },
            {
                "strategyName": "Bull Put Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52951,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17250,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317250PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 124.45,
                            "greeks": {
                                "theta": -10.514950514595519,
                                "delta": 0.40952832865545397,
                                "gamma": 0.0010328325926315686,
                                "vega": 9.297302661085562,
                                "iv": 15.72919188765809
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52977,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17450,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317450PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 221.2,
                            "greeks": {
                                "theta": -9.83277473714427,
                                "delta": 0.6241770713469666,
                                "gamma": 0.001052911599585305,
                                "vega": 9.077628081726338,
                                "iv": 15.064677922055125
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 5162.500000000001,
                "maxProfit": 4837.499999999999,
                "isInfiniteProfit": false,
                "isInfiniteLoss": false,
                "breakEven": [
                    17353.25
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.608323288978811,
                                "delta": 0.4846549379837184,
                                "gamma": 0.0010771455204965344,
                                "vega": 9.53671816695399,
                                "iv": 15.470485552214086
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52958,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17400,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317400CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 114.3,
                            "greeks": {
                                "theta": -10.307157378836926,
                                "delta": 0.4301508202120405,
                                "gamma": 0.0010764004479667598,
                                "vega": 9.39712002408225,
                                "iv": 15.2545808814466
                            }
                        },
                        "action": "SELL",
                        "quantity": 100
                    }
                ],
                "maxLoss": 0,
                "maxProfit": 6989.999999999999,
                "isInfiniteProfit": false,
                "isInfiniteLoss": true,
                "breakEven": [
                    17539.8
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.608323288978811,
                                "delta": 0.4846549379837184,
                                "gamma": 0.0010771455204965344,
                                "vega": 9.53671816695399,
                                "iv": 15.470485552214086
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52972,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17450,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317450CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 92.8,
                            "greeks": {
                                "theta": -9.83277473714427,
                                "delta": 0.37582292865303335,
                                "gamma": 0.001052911599585305,
                                "vega": 9.077628081726338,
                                "iv": 15.064677922055125
                            }
                        },
                        "action": "SELL",
                        "quantity": 100
                    }
                ],
                "maxLoss": 0,
                "maxProfit": 7339.999999999999,
                "isInfiniteProfit": false,
                "isInfiniteLoss": true,
                "breakEven": [
                    17596.8
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.608323288978811,
                                "delta": 0.4846549379837184,
                                "gamma": 0.0010771455204965344,
                                "vega": 9.53671816695399,
                                "iv": 15.470485552214086
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52978,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17500,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317500CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 73.35,
                            "greeks": {
                                "theta": -9.120987916533148,
                                "delta": 0.3217668041476536,
                                "gamma": 0.0010127861531965417,
                                "vega": 8.574685558523738,
                                "iv": 14.793802751228213
                            }
                        },
                        "action": "SELL",
                        "quantity": 100
                    }
                ],
                "maxLoss": 0,
                "maxProfit": 7894.999999999999,
                "isInfiniteProfit": false,
                "isInfiniteLoss": true,
                "breakEven": [
                    17657.9
                ]
            },
            {
                "strategyName": "Bull Call Spread",
                "legs": [
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.608323288978811,
                                "delta": 0.4846549379837184,
                                "gamma": 0.0010771455204965344,
                                "vega": 9.53671816695399,
                                "iv": 15.470485552214086
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52982,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17550,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317550CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 57.15,
                            "greeks": {
                                "theta": -8.299359242797577,
                                "delta": 0.270413390425581,
                                "gamma": 0.0009486131262055663,
                                "vega": 7.915989911949939,
                                "iv": 14.58127424120903
                            }
                        },
                        "action": "SELL",
                        "quantity": 100
                    }
                ],
                "maxLoss": 0,
                "maxProfit": 8775,
                "isInfiniteProfit": false,
                "isInfiniteLoss": true,
                "breakEven": [
                    17725.5
                ]
            }
        ],
        "underlyingPrice": 17331.8
    },
    "message": "-",
    "status": "success"
}
```

## BETWEEN ( 17200 <  17331.8 < 17400 )
>{
>    "symbol":"NIFTY",
>    "token": 26000,
>    "prediction":"BETWEEN",
>    "expiryDate":"20221013",
>    "instrumentPriceRange":[
>        17200, 17400
>    ]
>}

```
{
    "data": {
        "tradingOpportunities": [
            {
                "strategyName": "Short Straddle",
                "legs": [
                    {
                        "option": {
                            "token": 52957,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 166.75,
                            "greeks": {
                                "theta": -10.609199171513158,
                                "delta": 0.5153450620079121,
                                "gamma": 0.0010771455201194096,
                                "vega": 9.536324490607415,
                                "iv": 15.471124206669629
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.609199171513158,
                                "delta": 0.4846549379920879,
                                "gamma": 0.0010771455201194096,
                                "vega": 9.536324490607415,
                                "iv": 15.471124206669629
                            }
                        },
                        "action": "SELL",
                        "quantity": 50
                    }
                ],
                "maxLoss": 0,
                "maxProfit": 15277.5,
                "isInfiniteProfit": false,
                "isInfiniteLoss": true,
                "breakEven": [
                    17655.55,
                    17044.45
                ]
            },
            {
                "strategyName": "Long Straddle",
                "legs": [
                    {
                        "option": {
                            "token": 52957,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "PE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350PE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 166.75,
                            "greeks": {
                                "theta": -10.609199171513158,
                                "delta": 0.5153450620079121,
                                "gamma": 0.0010771455201194096,
                                "vega": 9.536324490607415,
                                "iv": 15.471124206669629
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    },
                    {
                        "option": {
                            "token": 52956,
                            "instrumentName": "OPTIDX",
                            "symbol": "NIFTY",
                            "strikePrice": 17350,
                            "optionType": "CE",
                            "lotSize": 50,
                            "securityDesc": "NIFTY22O1317350CE",
                            "marketSegmentId": 2,
                            "expYYYYMMDD": "20221013",
                            "ltp": 138.8,
                            "greeks": {
                                "theta": -10.609199171513158,
                                "delta": 0.4846549379920879,
                                "gamma": 0.0010771455201194096,
                                "vega": 9.536324490607415,
                                "iv": 15.471124206669629
                            }
                        },
                        "action": "BUY",
                        "quantity": 50
                    }
                ],
                "maxLoss": 15277.5,
                "maxProfit": 0,
                "isInfiniteProfit": true,
                "isInfiniteLoss": false,
                "breakEven": [
                    17655.55,
                    17044.45
                ]
            }
        ],
        "underlyingPrice": 17331.8
    },
    "message": "-",
    "status": "success"
}
```
