# Marbel-Heroes

**Marbel Heores**  is a application that present Marbel Heroes and alow to search for a specific hero, you can tap the hero you want to get a description of this hero. 
This app was created using the Marvel API https://developer.marvel.com

In order to use the app you will need to create an developer account and get your keys the app have a file name **KeysPlaceHolder.swift** where you will put your keys, This is the only step you will nedd to make use of this app. 


```swift
import Foundation

struct Secrets {
    struct MarvelKeys {
        static let publickey = "5837aadbfc4e8308242d17f415ddb69f"
        static let privateKey = "81c2289aec96a3484c481de45365885daf3a72e9"
        
    }
}
```
