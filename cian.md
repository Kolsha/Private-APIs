# Приватные API / [Cian.ru](https://cian.ru/)
[![Telegram: @Kolsha](https://img.shields.io/badge/contact-@Kolsha-blue.svg?style=flat)](https://t.me/Kolsha)

API работает. \
[Демо](https://kolsha.ru/apis/cian/).

### Список методов
Метод | Описание | Статус 
|---|---|---|
| Список объявлений | Получает список объявлений по фильтру | работает|
| Детальная информация об объявлении | Все, что есть на сайте, c номером телефона| работает|

При запросах капчи не замечено.

Примеры ответов:
<details>
  <summary>Список объявлений</summary>

  ```json
  {
    "searchUuid": null,
    "mlRankingModelVersion": null,
    "mlRankingGuid": null,
    "items": [
        {
            "village": null,
            "newBuilding": null,
            "type": "offer",
            "offer": {
                "analyticsUrl": "/rent/flat/mo_id=0/obl_id=4598/city_id=4897/object_type=1/ga_obj_type=None/spec=none/rent_type=/220243540/from_developer=0/repres=0/owner=1/pod_snos=0/",
                "services": [],
                "formattedVatType": null,
                "formattedShortPrice": "26 000 ₽/мес",
                "promoName": null,
                "newFlat": 0,
                "category": "flatRent",
                "newBuilding": null,
                "hasVideos": false,
                "formattedPricePerMeter": null,
                "isConfirmedHomeOwner": false,
                "newbuildingVasPromotion": null,
                "formattedFullPrice": "26 000 ₽/мес",
                "photos": [
                    {
                        "isLayout": null,
                        "small": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217432-4.jpg",
                        "full": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217432-1.jpg"
                    },
                    {
                        "isLayout": null,
                        "small": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217442-4.jpg",
                        "full": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217442-1.jpg"
                    },
                    {
                        "isLayout": null,
                        "small": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217436-4.jpg",
                        "full": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217436-1.jpg"
                    },
                    {
                        "isLayout": null,
                        "small": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217445-4.jpg",
                        "full": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217445-1.jpg"
                    },
                    {
                        "isLayout": null,
                        "small": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217447-4.jpg",
                        "full": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217447-1.jpg"
                    },
                    {
                        "isLayout": null,
                        "small": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217451-4.jpg",
                        "full": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217451-1.jpg"
                    },
                    {
                        "isLayout": null,
                        "small": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217450-4.jpg",
                        "full": "https://cdn-p.cian.site/images2/4/712/277/kvartira-novosibirsk-ulica-gogolya-772217450-1.jpg"
                    }
                ],
                "isFromDeveloper": null,
                "userId": 19837067,
                "formattedCardInfo": "Студия  •  40 м²  •  5/20 этаж",
                "formattedCommunalInfo": "Комм. платежи включены (без счетчиков)",
                "formattedAddress": "улица Гоголя, 40/1, Новосибирск, Новосибирская область",
                "formattedAdditionalInfo": "Залог 26 000 ₽, без комиссии, предоплата 1 месяц, на длительный срок",
                "formattedFullInfo": "Студия  •  40 м²  •  5/20 этаж",
                "isByHomeowner": true,
                "geo": {
                    "userInput": "Россия, Новосибирск, улица Гоголя, 40/1",
                    "address": [
                        {
                            "name": "Новосибирская",
                            "locationTypeId": 2,
                            "id": 4598,
                            "fullName": "Новосибирская область",
                            "isFormingAddress": true
                        },
                        {
                            "name": "Новосибирск",
                            "locationTypeId": 1,
                            "id": 4897,
                            "fullName": "Новосибирск",
                            "isFormingAddress": true
                        },
                        {
                            "name": "Гоголя",
                            "locationTypeId": null,
                            "id": 246147,
                            "fullName": "улица Гоголя",
                            "isFormingAddress": true
                        },
                        {
                            "name": "40/1",
                            "locationTypeId": null,
                            "id": 4303542,
                            "fullName": "40/1",
                            "isFormingAddress": true
                        }
                    ],
                    "highways": [],
                    "coordinates": {
                        "lng": 82.937021,
                        "lat": 55.043092
                    },
                    "undergrounds": [],
                    "railways": [],
                    "districts": [
                        {
                            "name": "р-н Центральный",
                            "type": "raion"
                        }
                    ],
                    "sortedGeo": [
                        {
                            "underground": null,
                            "railway": null,
                            "highway": null,
                            "district": {
                                "name": "р-н Центральный",
                                "type": "raion"
                            }
                        }
                    ]
                },
                "status": "published",
                "formattedPremisesInfo": null,
                "videos": [],
                "id": 220243540,
                "dealType": "rent",
                "creationDate": "2019-10-24T10:42:30.29",
                "formattedShortInfo": "Студия  •  5/20 этаж",
                "promosInfo": null,
                "offerType": "flat",
                "siteUrl": "https://novosibirsk.cian.ru/rent/flat/220243540/",
                "title": null,
                "userTrust": "new",
                "isPro": false,
                "isAgentAvailable": true,
                "agent": {
                    "phones": [
                        "+79139120814",
                        "+79139854814"
                    ],
                    "workingTimeMessage": null,
                    "workingTimeTitle": null
                },
                "isChatEnabled": true,
                "priceChanged": "reduced"
            }
        },
        {
            "village": null,
            "newBuilding": null,
            "type": "offer",
            "offer": {
                "hasVideos": false,
                "formattedShortPrice": "28 000 ₽/мес",
                "geo": {
                    "railways": [],
                    "undergrounds": [],
                    "districts": [
                        {
                            "type": "raion",
                            "name": "р-н Советский"
                        },
                        {
                            "type": "mikroraion",
                            "name": "мкр. Нижняя зона Академгородка"
                        }
                    ],
                    "address": [
                        {
                            "fullName": "Новосибирская область",
                            "isFormingAddress": true,
                            "locationTypeId": 2,
                            "name": "Новосибирская",
                            "id": 4598
                        },
                        {
                            "fullName": "Новосибирск",
                            "isFormingAddress": true,
                            "locationTypeId": 1,
                            "name": "Новосибирск",
                            "id": 4897
                        },
                        {
                            "fullName": "Академгородок мкр",
                            "isFormingAddress": true,
                            "locationTypeId": 174,
                            "name": "Академгородок",
                            "id": 201245
                        },
                        {
                            "fullName": "улица Полевая",
                            "isFormingAddress": true,
                            "locationTypeId": null,
                            "name": "Полевая",
                            "id": 792525
                        },
                        {
                            "fullName": "3",
                            "isFormingAddress": true,
                            "locationTypeId": null,
                            "name": "3",
                            "id": 1924616
                        }
                    ],
                    "coordinates": {
                        "lng": 83.099131,
                        "lat": 54.865788
                    },
                    "userInput": "Россия, Новосибирск, Советский район, микрорайон Академгородок, Полевая улица, 3",
                    "highways": [],
                    "sortedGeo": [
                        {
                            "underground": null,
                            "railway": null,
                            "highway": null,
                            "district": {
                                "type": "raion",
                                "name": "р-н Советский"
                            }
                        }
                    ]
                },
                "formattedFullPrice": "28 000 ₽/мес",
                "status": "published",
                "dealType": "rent",
                "formattedShortInfo": "2-комн.кв.  •  8/9 этаж",
                "newFlat": 0,
                "category": "flatRent",
                "services": [],
                "isFromDeveloper": null,
                "analyticsUrl": "/rent/flat/mo_id=0/obl_id=4598/city_id=201245/object_type=1/ga_obj_type=2/spec=none/rent_type=/220892631/from_developer=0/repres=0/owner=1/pod_snos=0/",
                "formattedFullInfo": "2-комн.кв.  •  50,7 м²  •  8/9 этаж",
                "promoName": null,
                "formattedCardInfo": "2-комн.кв.  •  50,7 м²  •  8/9 этаж",
                "formattedAdditionalInfo": "Без депозита, без комиссии, предоплата 1 месяц, на несколько месяцев",
                "videos": [],
                "offerType": "flat",
                "isByHomeowner": true,
                "promosInfo": null,
                "formattedCommunalInfo": "Комм. платежи включены (без счетчиков)",
                "id": 220892631,
                "title": null,
                "newBuilding": null,
                "siteUrl": "https://novosibirsk.cian.ru/rent/flat/220892631/",
                "formattedPremisesInfo": null,
                "formattedVatType": null,
                "isConfirmedHomeOwner": false,
                "photos": [
                    {
                        "small": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854384-4.jpg",
                        "isLayout": null,
                        "full": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854384-1.jpg"
                    },
                    {
                        "small": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854383-4.jpg",
                        "isLayout": null,
                        "full": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854383-1.jpg"
                    },
                    {
                        "small": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854386-4.jpg",
                        "isLayout": null,
                        "full": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854386-1.jpg"
                    },
                    {
                        "small": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854387-4.jpg",
                        "isLayout": null,
                        "full": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854387-1.jpg"
                    },
                    {
                        "small": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854388-4.jpg",
                        "isLayout": null,
                        "full": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854388-1.jpg"
                    },
                    {
                        "small": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854391-4.jpg",
                        "isLayout": null,
                        "full": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854391-1.jpg"
                    },
                    {
                        "small": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854389-4.jpg",
                        "isLayout": null,
                        "full": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854389-1.jpg"
                    },
                    {
                        "small": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854390-4.jpg",
                        "isLayout": null,
                        "full": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854390-1.jpg"
                    },
                    {
                        "small": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854392-4.jpg",
                        "isLayout": null,
                        "full": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854392-1.jpg"
                    },
                    {
                        "small": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854394-4.jpg",
                        "isLayout": null,
                        "full": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854394-1.jpg"
                    },
                    {
                        "small": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854393-4.jpg",
                        "isLayout": null,
                        "full": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854393-1.jpg"
                    },
                    {
                        "small": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854395-4.jpg",
                        "isLayout": null,
                        "full": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854395-1.jpg"
                    }
                ],
                "formattedAddress": "улица Полевая, 3, Академгородок мкр, Новосибирск, Новосибирская область",
                "formattedPricePerMeter": null,
                "newbuildingVasPromotion": null,
                "userId": 45135791,
                "creationDate": "2019-11-04T12:20:45.38",
                "userTrust": "new",
                "isPro": false,
                "isAgentAvailable": true,
                "agent": {
                    "phones": [
                        "+79139258117"
                    ],
                    "workingTimeMessage": null,
                    "workingTimeTitle": null
                },
                "isChatEnabled": true,
                "priceChanged": "none"
            }
        },
        {...}

    ],
    "isPaginationEnd": false,
    "itemsCount": 20,
    "extensionsOffset": 0,
    "totalCount": 120
}
  ```
</details>

<details>
  <summary>Детальная информация об объявлении</summary>

  ```json
  {
    "status": "ok",
    "data": {
        "search_uuid": "2440a694-0227-11ea-a1e9-e2ada769c9e2",
        "newobjects": [],
        "users": [
            {
                "isPassportChecked": false,
                "availability": {
                    "available": true,
                    "userId": 45135791
                },
                "id": 45135791
            }
        ],
        "villages": [],
        "agents": [],
        "exp_phone": false,
        "suggest": {
            "suggestions_query_json": null,
            "suggestions_query_qs": null,
            "suggest_parsed_offers": []
        },
        "items_count": 1,
        "ml_ranking_guid": null,
        "offers_count": 1,
        "notes": [],
        "offers": [
            {
                "roomType": "separate",
                "isObjectOnPremoderation": false,
                "userTrust": "new",
                "hasKitchenFurniture": true,
                "videos": [],
                "windowsViewType": "street",
                "hasFridge": true,
                "phones": [
                    {
                        "number": "9139258117",
                        "countryCode": "+7"
                    }
                ],
                "floorNumber": 8,
                "userId": 45135791,
                "analyticsUrl": "/rent/flat/mo_id=0/obl_id=4598/city_id=4897/object_type=/ga_obj_type=2/spec=none/rent_type=few_months/220892631/from_developer=0/repres=0/owner=1/pod_snos=0/",
                "hasFurniture": true,
                "hasConditioner": true,
                "chat": [],
                "multiQs": "deal_type=rent&offer_type=flat&engine_version=2&multi_id=220892631",
                "bedsCount": 0,
                "bti": {
                    "entrances": 6,
                    "yearRelease": 1991,
                    "overlapType": "Железобетонные",
                    "gasSupplyType": "Отсутствует",
                    "seriesName": "111-90",
                    "lifts": 6,
                    "heatSupplyType": "Центральное отопление",
                    "houseMaterialType": "панельный",
                    "isEmergency": false
                },
                "id": 220892631,
                "hasBathtub": true,
                "category": "flatRent",
                "akkCanRetry": false,
                "creationDate": "2019-11-04T12:20:45.38",
                "stats": {
                    "total": 5,
                    "daily": 0
                },
                "isByHomeowner": true,
                "publishTerms": {
                    "autoprolong": true,
                    "terms": [
                        {
                            "services": [
                                "paid"
                            ],
                            "type": "periodical",
                            "days": 14
                        }
                    ]
                },
                "hasShower": false,
                "chatEnabled": true,
                "hasTv": false,
                "isHiddenByUser": false,
                "hasWasher": true,
                "identificationPending": false,
                "publishTillDate": "2019-11-18T12:25:04",
                "kitchenArea": "7.0",
                "platform": {
                    "version": "1.111",
                    "type": "ios"
                },
                "bargainTerms": {
                    "paymentPeriod": "monthly",
                    "priceRur": 28000,
                    "includedOptions": [],
                    "clientFee": 0,
                    "priceUsd": 439,
                    "price": 28000,
                    "utilitiesTerms": {
                        "price": 0,
                        "includedInPrice": true
                    },
                    "priceEur": 396,
                    "currency": "rur",
                    "deposit": 0,
                    "bargainAllowed": false,
                    "depositPrices": {
                        "rur": 0,
                        "usd": 0,
                        "eur": 0
                    },
                    "prepayMonths": 1,
                    "leaseTermType": "fewMonths",
                    "agentFee": 0,
                    "priceType": "all",
                    "utilitiesTermsPrices": {
                        "rur": 0,
                        "usd": 0,
                        "eur": 0
                    }
                },
                "multiCount": 0,
                "cianUserId": 45135791,
                "promoInfoList": [],
                "offerType": "flat",
                "hasDishwasher": true,
                "flatType": "rooms",
                "isInHiddenBase": false,
                "isRentByParts": false,
                "akkCheckStatus": "notSpecified",
                "loggiasCount": 2,
                "descriptionMinhash": "[80735524, 8359824, 13184479, 324683335, 222151216, 518656449, 381977867, 172375708, 612953033, 228480544, 506748344, 831746286, 599200179, 370532192, 142727182, 289800561, 904381691, 105139689, 43747950, 494169306, 458649133, 142599862, 636445489, 61917607, 160686060, 67242399, 541933216, 227659883, 9375242, 289830691, 592085023, 266297379]",
                "description": "Чистая уютная квартира после ремонта, расположена в 2 минутах от остановки, вблизи развитая инфраструктура",
                "messagingState": false,
                "favoritesCount": 0,
                "totalArea": "50.7",
                "specialty": {
                    "additionalTypes": [],
                    "types": []
                },
                "publishDate": "2019-11-04T12:20:45",
                "hasInternet": false,
                "separateWcsCount": 1,
                "demolishedInMoscowProgramm": false,
                "petsAllowed": false,
                "estimation": {
                    "district": {
                        "priceSqm": 70717,
                        "districtTitle": "Советский",
                        "roomSalePrice": 3566253.6,
                        "roomSalePriceDiff": 8.6,
                        "roomRentPrice": 20361.6,
                        "roomRentPriceDiff": 4.4,
                        "priceSqmDiff": 8.9
                    },
                    "house": {
                        "roomRentPrice": 16848,
                        "priceSqm": 75496,
                        "priceSqmDiff": -4.1,
                        "roomRentPriceDiff": -15.4
                    },
                    "priceRent": 17795.7,
                    "priceMax": 4138438.2,
                    "priceSale": 3893962.8000000003,
                    "priceMin": 3649487.4000000004
                },
                "services": [
                    "paid"
                ],
                "isPenthouse": false,
                "categoriesIds": [
                    1000,
                    1100,
                    1110,
                    1111
                ],
                "geo": {
                    "districts": [
                        {
                            "locationId": 4897,
                            "parentId": 217,
                            "type": "mikroraion",
                            "id": 3062,
                            "name": "Нижняя зона Академгородка"
                        },
                        {
                            "locationId": 4897,
                            "type": "raion",
                            "id": 217,
                            "name": "Советский"
                        }
                    ],
                    "countryId": 138,
                    "undergrounds": [],
                    "railways": [],
                    "coordinates": {
                        "lat": 54.865788,
                        "lng": 83.099131
                    },
                    "highways": [],
                    "userInput": "Россия, Новосибирск, Советский район, микрорайон Академгородок, Полевая улица, 3",
                    "address": [
                        {
                            "name": "Новосибирская",
                            "id": 4598,
                            "locationTypeId": 2,
                            "fullName": "Новосибирская область",
                            "type": "location",
                            "shortName": "Новосибирская область",
                            "isFormingAddress": true
                        },
                        {
                            "name": "Новосибирск",
                            "id": 4897,
                            "locationTypeId": 1,
                            "fullName": "Новосибирск",
                            "type": "location",
                            "shortName": "Новосибирск",
                            "isFormingAddress": true
                        },
                        {
                            "name": "Академгородок",
                            "id": 201245,
                            "locationTypeId": 174,
                            "fullName": "Академгородок мкр",
                            "type": "location",
                            "shortName": "Академгородок микрорайон",
                            "isFormingAddress": true
                        },
                        {
                            "name": "Полевая",
                            "id": 792525,
                            "shortName": "ул. Полевая",
                            "type": "street",
                            "fullName": "улица Полевая",
                            "isFormingAddress": true
                        },
                        {
                            "name": "3",
                            "id": 1924616,
                            "shortName": "3",
                            "type": "house",
                            "fullName": "3",
                            "isFormingAddress": true
                        }
                    ],
                    "locationPath": {
                        "countryId": 138,
                        "childToParent": [
                            201245,
                            4897,
                            4598
                        ]
                    }
                },
                "historyPriceChanges": [
                    {
                        "changeTime": 1572848474,
                        "priceData": {
                            "paymentPeriod": "monthly",
                            "currency": "rur",
                            "price": 28000
                        }
                    }
                ],
                "isAuction": false,
                "balconiesCount": 0,
                "status": "published",
                "childrenAllowed": true,
                "siteUrl": "https://www.cian.ru/rent/flat/220892631",
                "livingArea": "40.8",
                "photos": [
                    {
                        "thumbnail2Url": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854384-4.jpg",
                        "id": 777854384,
                        "thumbnailUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854384-2.jpg",
                        "fullUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854384-1.jpg",
                        "isDefault": true,
                        "miniUrl": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854384-3.jpg"
                    },
                    {
                        "thumbnail2Url": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854383-4.jpg",
                        "id": 777854383,
                        "thumbnailUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854383-2.jpg",
                        "fullUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854383-1.jpg",
                        "isDefault": false,
                        "miniUrl": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854383-3.jpg"
                    },
                    {
                        "thumbnail2Url": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854386-4.jpg",
                        "id": 777854386,
                        "thumbnailUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854386-2.jpg",
                        "fullUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854386-1.jpg",
                        "isDefault": false,
                        "miniUrl": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854386-3.jpg"
                    },
                    {
                        "thumbnail2Url": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854387-4.jpg",
                        "id": 777854387,
                        "thumbnailUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854387-2.jpg",
                        "fullUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854387-1.jpg",
                        "isDefault": false,
                        "miniUrl": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854387-3.jpg"
                    },
                    {
                        "thumbnail2Url": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854388-4.jpg",
                        "id": 777854388,
                        "thumbnailUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854388-2.jpg",
                        "fullUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854388-1.jpg",
                        "isDefault": false,
                        "miniUrl": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854388-3.jpg"
                    },
                    {
                        "thumbnail2Url": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854391-4.jpg",
                        "id": 777854391,
                        "thumbnailUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854391-2.jpg",
                        "fullUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854391-1.jpg",
                        "isDefault": false,
                        "miniUrl": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854391-3.jpg"
                    },
                    {
                        "thumbnail2Url": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854389-4.jpg",
                        "id": 777854389,
                        "thumbnailUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854389-2.jpg",
                        "fullUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854389-1.jpg",
                        "isDefault": false,
                        "miniUrl": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854389-3.jpg"
                    },
                    {
                        "thumbnail2Url": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854390-4.jpg",
                        "id": 777854390,
                        "thumbnailUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854390-2.jpg",
                        "fullUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854390-1.jpg",
                        "isDefault": false,
                        "miniUrl": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854390-3.jpg"
                    },
                    {
                        "thumbnail2Url": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854392-4.jpg",
                        "id": 777854392,
                        "thumbnailUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854392-2.jpg",
                        "fullUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854392-1.jpg",
                        "isDefault": false,
                        "miniUrl": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854392-3.jpg"
                    },
                    {
                        "thumbnail2Url": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854394-4.jpg",
                        "id": 777854394,
                        "thumbnailUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854394-2.jpg",
                        "fullUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854394-1.jpg",
                        "isDefault": false,
                        "miniUrl": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854394-3.jpg"
                    },
                    {
                        "thumbnail2Url": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854393-4.jpg",
                        "id": 777854393,
                        "thumbnailUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854393-2.jpg",
                        "fullUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854393-1.jpg",
                        "isDefault": false,
                        "miniUrl": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854393-3.jpg"
                    },
                    {
                        "thumbnail2Url": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854395-4.jpg",
                        "id": 777854395,
                        "thumbnailUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854395-2.jpg",
                        "fullUrl": "https://cdn-p.cian.site/images2/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854395-1.jpg",
                        "isDefault": false,
                        "miniUrl": "https://www.cian.ru/image-temp/3/458/777/kvartira-akademgorodok-polevaya-ulica-777854395-3.jpg"
                    }
                ],
                "editDate": "2019-11-04T12:20:45",
                "canProlong": false,
                "objectGuid": "35d6971b-0496-475e-b666-fec5c8fd68d4",
                "callValue": 1,
                "isReliableEnable": true,
                "homeownerProofs": [],
                "cianId": 220892631,
                "flags": {
                    "isArchived": false
                },
                "repairType": "cosmetic",
                "publishedUserId": 45135791,
                "showJkReliableFlag": false,
                "dealType": "rent",
                "roomsCount": 2,
                "building": {
                    "cargoLiftsCount": 0,
                    "cranageTypes": [],
                    "hasGarbageChute": false,
                    "materialType": "panel",
                    "series": "Панель",
                    "buildYear": 1996,
                    "liftTypes": [],
                    "totalArea": "50.7",
                    "parking": {
                        "type": "ground"
                    },
                    "passengerLiftsCount": 1,
                    "floorsCount": 9,
                    "ceilingHeight": "2.5"
                },
                "vasType": "classic",
                "combinedWcsCount": 0
            }
        ],
        "all_agents": [],
        "ml_ranking_model_version": null,
        "estimation": {
            "price": 18000,
            "severalOffers": null
        }
    },
    "data_type": "offers"
}
  ```
</details>
