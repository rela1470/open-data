# open-data
トヨクモ社の安否確認サービスで地域コードを指定したかったんだけど、APIに設定すべき値が取れるやつがないので、jsonをつくった

## change date
### v2 2023-10-11
### v1 2021-11-18

## data from

* https://anpi-guide.toyokumo.co.jp/area_code/
* https://www.data.jma.go.jp/svd/eqev/data/joho/shindo-name.html

## sample
```
[
      {
        "toyokumo_id": "01",
        "nest_level": "1",
        "prefectures_name": "北海道",
        "zone_name": "北海道",
        "region_name": "北海道地方",
        "city_name": ""
    },
    {
        "toyokumo_id": "142",
        "nest_level": "2",
        "prefectures_name": "北海道",
        "zone_name": "北海道道東",
        "region_name": "紋別地方",
        "city_name": "紋別市、紋別郡［遠軽町、湧別町、滝上町、興部町、西興部村、雄武町］"
    }
]
```