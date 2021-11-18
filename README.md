# open-data
トヨクモ社の安否確認サービスで地域コードを指定したかったんだけど、APIに設定すべき値が取れるやつがないので、jsonをつくった

## data from

* https://anpi-guide.toyokumo.co.jp/area_code/
* https://www.data.jma.go.jp/svd/eqev/data/joho/shindo-name.html

## sample
```
[
  {
    "toyokumo_id": "01",
    "region_name": "北海道",
    "prefectures_name": "北海道",
    "local_name": "北海道地方",
    "zone_name": "",
    "nest_level": 1
  },
  {
    "toyokumo_id": 142,
    "region_name": "紋別地方",
    "prefectures_name": "北海道",
    "local_name": "北海道地方",
    "zone_name": "北海道道東",
    "nest_level": 2
  }
]
```