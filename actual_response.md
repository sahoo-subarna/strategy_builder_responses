# strategy_builder_responses
#### Underlying Price at : 17331.8

## BELOW (17331.8 < 17400)
```
{
    "symbol":"NIFTY",
    "token": 26000,
    "prediction":"BELOW",
    "expiryDate":"20221013",
    "instrumentPriceRange":[
        17400
    ]
}
```
> Response : BELOW (17331.8 < 17400)
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
                                "theta": -10.626995169211296,
                                "delta": 0.4846549380199935,
                                "gamma": 0.001077145518862004,
                                "vega": 9.52833637191586,
                                "iv": 15.484094503335655
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
                                "theta": -10.325299208921635,
                                "delta": 0.43015082059276366,
                                "gamma": 0.0010764004428557843,
                                "vega": 9.38886092303175,
                                "iv": 15.267999959178269
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
                "breakEven": [
                    17374.5
                ]
            }
        ],
        "underlyingPrice": 17331.8
    },
    "message": "-",
    "status": "success"
}
```



## BELOW (17331.8 > 17200)
```
{
    "symbol":"NIFTY",
    "token": 26000,
    "prediction":"BELOW",
    "expiryDate":"20221013",
    "instrumentPriceRange":[
        17200
    ]
}
```
> Response : BELOW (17331.8 > 17200)
```
{
    "data": {
        "tradingOpportunities": [
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
                                "theta": -10.627372475564394,
                                "delta": 0.5153450620375909,
                                "gamma": 0.0010771455214567162,
                                "vega": 9.528167215337488,
                                "iv": 15.484369359910488
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
                                "theta": -8.386448729971244,
                                "delta": 0.22740613756042738,
                                "gamma": 0.0007819060854282404,
                                "vega": 7.211499434085371,
                                "iv": 16.14468265324831
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
```
{
    "symbol":"NIFTY",
    "token": 26000,
    "prediction":"ABOVE",
    "expiryDate":"20221013",
    "instrumentPriceRange":[
        17400
    ]
}
```
> Response : ABOVE (17331.8 < 17400)
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
                                "theta": -10.627770215508027,
                                "delta": 0.4846549379670872,
                                "gamma": 0.0010771455212459247,
                                "vega": 9.527988920734147,
                                "iv": 15.484659117646515
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
                                "theta": -10.32605222566793,
                                "delta": 0.43015082023583695,
                                "gamma": 0.0010764004476473065,
                                "vega": 9.388518556374668,
                                "iv": 15.268556657247245
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
                                "theta": -10.627770215508027,
                                "delta": 0.4846549379670872,
                                "gamma": 0.0010771455212459247,
                                "vega": 9.527988920734147,
                                "iv": 15.484659117646515
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
                                "theta": -9.850799915003039,
                                "delta": 0.37582292820282054,
                                "gamma": 0.001052911602894021,
                                "vega": 9.069319051138724,
                                "iv": 15.07847965694964
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
                                "theta": -10.627770215508027,
                                "delta": 0.4846549379670872,
                                "gamma": 0.0010771455212459247,
                                "vega": 9.527988920734147,
                                "iv": 15.484659117646515
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
                                "theta": -9.13770832667046,
                                "delta": 0.3217668045369623,
                                "gamma": 0.0010127861514289678,
                                "vega": 8.566836894130786,
                                "iv": 14.807356405071914
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
                                "theta": -10.627770215508027,
                                "delta": 0.4846549379670872,
                                "gamma": 0.0010771455212459247,
                                "vega": 9.527988920734147,
                                "iv": 15.484659117646515
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
                                "theta": -8.314573423171158,
                                "delta": 0.2704133901741208,
                                "gamma": 0.000948613126905897,
                                "vega": 7.908744163597391,
                                "iv": 14.594633132219315
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
                                "theta": -10.627770215508027,
                                "delta": 0.4846549379670872,
                                "gamma": 0.0010771455212459247,
                                "vega": 9.527988920734147,
                                "iv": 15.484659117646515
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
                                "theta": -10.32605222566793,
                                "delta": 0.43015082023583695,
                                "gamma": 0.0010764004476473065,
                                "vega": 9.388518556374668,
                                "iv": 15.268556657247245
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
                                "theta": -10.627770215508027,
                                "delta": 0.4846549379670872,
                                "gamma": 0.0010771455212459247,
                                "vega": 9.527988920734147,
                                "iv": 15.484659117646515
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
                                "theta": -9.850799915003039,
                                "delta": 0.37582292820282054,
                                "gamma": 0.001052911602894021,
                                "vega": 9.069319051138724,
                                "iv": 15.07847965694964
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
                                "theta": -10.627770215508027,
                                "delta": 0.4846549379670872,
                                "gamma": 0.0010771455212459247,
                                "vega": 9.527988920734147,
                                "iv": 15.484659117646515
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
                                "theta": -9.13770832667046,
                                "delta": 0.3217668045369623,
                                "gamma": 0.0010127861514289678,
                                "vega": 8.566836894130786,
                                "iv": 14.807356405071914
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
                                "theta": -10.627770215508027,
                                "delta": 0.4846549379670872,
                                "gamma": 0.0010771455212459247,
                                "vega": 9.527988920734147,
                                "iv": 15.484659117646515
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
                                "theta": -8.314573423171158,
                                "delta": 0.2704133901741208,
                                "gamma": 0.000948613126905897,
                                "vega": 7.908744163597391,
                                "iv": 14.594633132219315
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
```
{

    "symbol":"NIFTY",
    "token": 26000,
    "prediction":"ABOVE",
    "expiryDate":"20221013",
    "instrumentPriceRange":[
        17200
    ]
}
```
> Response : ABOVE (17331.8 > 17200)
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
                                "theta": -10.628120976916739,
                                "delta": 0.4846549379797089,
                                "gamma": 0.0010771455206772017,
                                "vega": 9.52783169517946,
                                "iv": 15.484914649277925
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
                                "theta": -10.326393040134718,
                                "delta": 0.43015082035541485,
                                "gamma": 0.001076400446042047,
                                "vega": 9.388363632773622,
                                "iv": 15.26880863821134
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
                                "theta": -10.628120976916739,
                                "delta": 0.4846549379797089,
                                "gamma": 0.0010771455206772017,
                                "vega": 9.52783169517946,
                                "iv": 15.484914649277925
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
                                "theta": -9.851125082235145,
                                "delta": 0.37582292884088486,
                                "gamma": 0.0010529115982047417,
                                "vega": 9.069169399113317,
                                "iv": 15.078728552907705
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
                                "theta": -10.628120976916739,
                                "delta": 0.4846549379797089,
                                "gamma": 0.0010771455206772017,
                                "vega": 9.52783169517946,
                                "iv": 15.484914649277925
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
                                "theta": -9.138009911662902,
                                "delta": 0.3217668046419967,
                                "gamma": 0.0010127861509520815,
                                "vega": 8.566695530121603,
                                "iv": 14.807600760832429
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
                                "theta": -10.628120976916739,
                                "delta": 0.4846549379797089,
                                "gamma": 0.0010771455206772017,
                                "vega": 9.52783169517946,
                                "iv": 15.484914649277925
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
                                "theta": -8.314847764120003,
                                "delta": 0.2704133888909478,
                                "gamma": 0.0009486131304796062,
                                "vega": 7.908613639150554,
                                "iv": 14.594873879104853
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
                                "theta": -10.705839147744678,
                                "delta": 0.46182131753984973,
                                "gamma": 0.001061117216754427,
                                "vega": 9.491190273302374,
                                "iv": 15.65836591180414
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
                                "theta": -10.326393040134718,
                                "delta": 0.5698491796445851,
                                "gamma": 0.001076400446042047,
                                "vega": 9.388363632773622,
                                "iv": 15.26880863821134
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
                                "theta": -10.705839147744678,
                                "delta": 0.46182131753984973,
                                "gamma": 0.001061117216754427,
                                "vega": 9.491190273302374,
                                "iv": 15.65836591180414
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
                                "theta": -9.851125082235145,
                                "delta": 0.6241770711591151,
                                "gamma": 0.0010529115982047417,
                                "vega": 9.069169399113317,
                                "iv": 15.078728552907705
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
                                "theta": -10.534573931716507,
                                "delta": 0.4095283285351822,
                                "gamma": 0.0010328325941021987,
                                "vega": 9.288639279986585,
                                "iv": 15.743862255476415
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
                                "theta": -10.326393040134718,
                                "delta": 0.5698491796445851,
                                "gamma": 0.001076400446042047,
                                "vega": 9.388363632773622,
                                "iv": 15.26880863821134
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
                                "theta": -10.534573931716507,
                                "delta": 0.4095283285351822,
                                "gamma": 0.0010328325941021987,
                                "vega": 9.288639279986585,
                                "iv": 15.743862255476415
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
                                "theta": -9.851125082235145,
                                "delta": 0.6241770711591151,
                                "gamma": 0.0010529115982047417,
                                "vega": 9.069169399113317,
                                "iv": 15.078728552907705
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
                                "theta": -10.628120976916739,
                                "delta": 0.4846549379797089,
                                "gamma": 0.0010771455206772017,
                                "vega": 9.52783169517946,
                                "iv": 15.484914649277925
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
                                "theta": -10.326393040134718,
                                "delta": 0.43015082035541485,
                                "gamma": 0.001076400446042047,
                                "vega": 9.388363632773622,
                                "iv": 15.26880863821134
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
                                "theta": -10.628120976916739,
                                "delta": 0.4846549379797089,
                                "gamma": 0.0010771455206772017,
                                "vega": 9.52783169517946,
                                "iv": 15.484914649277925
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
                                "theta": -9.851125082235145,
                                "delta": 0.37582292884088486,
                                "gamma": 0.0010529115982047417,
                                "vega": 9.069169399113317,
                                "iv": 15.078728552907705
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
                                "theta": -10.628120976916739,
                                "delta": 0.4846549379797089,
                                "gamma": 0.0010771455206772017,
                                "vega": 9.52783169517946,
                                "iv": 15.484914649277925
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
                                "theta": -9.138009911662902,
                                "delta": 0.3217668046419967,
                                "gamma": 0.0010127861509520815,
                                "vega": 8.566695530121603,
                                "iv": 14.807600760832429
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
                                "theta": -10.628120976916739,
                                "delta": 0.4846549379797089,
                                "gamma": 0.0010771455206772017,
                                "vega": 9.52783169517946,
                                "iv": 15.484914649277925
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
                                "theta": -8.314847764120003,
                                "delta": 0.2704133888909478,
                                "gamma": 0.0009486131304796062,
                                "vega": 7.908613639150554,
                                "iv": 14.594873879104853
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
```
{
    "symbol":"NIFTY",
    "token": 26000,
    "prediction":"BETWEEN",
    "expiryDate":"20221013",
    "instrumentPriceRange":[
        17200, 17400
    ]
}
```
> RESPONSE : BETWEEN ( 17200 <  17331.8 < 17400 )
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
                                "theta": -10.62849089780812,
                                "delta": 0.5153450619556741,
                                "gamma": 0.0010771455177656039,
                                "vega": 9.52766590031525,
                                "iv": 15.485184150747955
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
                                "theta": -10.62849089780812,
                                "delta": 0.48465493804432586,
                                "gamma": 0.0010771455177656039,
                                "vega": 9.52766590031525,
                                "iv": 15.485184150747955
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
            }
        ],
        "underlyingPrice": 17331.8
    },
    "message": "-",
    "status": "success"
}
```
