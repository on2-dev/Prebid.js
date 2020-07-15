# Overview

```
Module Name: Alright Bidder Adapter
Module Type: Bidder Adapter
Maintainer: contato@alright.network
```

# Description

The Alright Bidder Adapter description

# Test Parameters
```
    var adUnits = [
        {
            code: 'test-div',
            mediaTypes: {
                banner: {
                    sizes: [[300, 250]],  // a display size
                }
            },
            bids: [
                {
                    bidder: "example",
                    params: {
                        placement: '12345'
                    }
                }
            ]
        },{
            code: 'test-div',
            mediaTypes: {
                banner: {
                    sizes: [[320, 50]],   // a mobile size
                }
            },
            bids: [
                {
                    bidder: "example",
                    params: {
                        placement: 67890
                    }
                }
            ]
        }
    ];
```