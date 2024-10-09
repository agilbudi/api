# references and usage

## Description
This data is manually collected based on data from references listed in the 'reference' data in 2024.
If there is any incorrect or outdated data, please visit the reference site listed.

## How to Use

1. Get json from
[`here`](https://agilbudi.github.io/api/simpleMedicines/medicines.json)
2. Create endpoint from template below

    Template JSON Format

    | Attribute | Type |  |
    | :---: | :--- | :--- |
    | `credit` | String |  |
    | `data` | Array |  |
    | `id` | Integer |  |
    | `name` | String |  |
    | `image` | String |  |
    | `detail` | String |  |
    | `benefit` | String |  |
    | `groups` | String |  |
    | `category` | Array |  |
    | `consumed` | String |  |
    | `form` | Array |  |
    | `forMother` | Object |  |
    | `pregnant` | String |  |
    | `breastfeeding` | String |  |
    | `trademark` | Array |  |
    | `beforeConsuming` | Object |  |
    | `detail` | String |  |
    | `point` | String |  |
    | `dose` | Array |  |
    | `effect` | Array |  |

Example:

```json
{
  "credit": "Data ini dikumpulkan secara manual berdasarkan data dari referensi ...",
  "data": [
    {
      "id": 1,
      "name": "Cetirizine",
      "image": "https://res-3.cloudinary.com/dk0z4ums3/image/...",
      "detail": "Cetirizine biasanya digunakan untuk ...",
      "benefit": "Meredakan gejala alergi",
      "groups": "Obat Resep",
      "category": [
        "Antihistamin"
      ],
      "consumed": "Dewasa dan anak usia ≥2 tahun",
      "form": [
        "Tablet",
        "Kaplet",
        "..."
      ],
      "forMother": {
        "pregnant": "Jika Anda sedang hamil, ...",
        "breastfeeding": "Jika Anda sedang menyusui, ..."
      },
      "trademark": [
        "Alerzin",
        "Cerini",
        "..."
      ],
      "beforeConsuming": {
        "detail": "Cetirizine merupakan ...",
        "point": [
          "Jangan mengonsumsi ...",
          "..."
        ]
      },
      "dose": [
        "Dewasa dan anak usia >6 tahun: 5–10 mg, ...",
        "Anak usia 2–6 tahun: 2,5 mg, ..."
      ],
      "effect": [
        "Kantuk",
        "Kelelahan",
        "..."
      ]
    },
    {
      "id": 2,
      ...
    }
 ],
  "reference": [
    "https://www.alodokter.com/",
    "https://www.halodoc.com/",
    "https://e-katalog.lkpp.go.id/"
  ]
}
```

3. Use endpoint to show the data.

## Use references

- _[https://www.alodokter.com](https://www.alodokter.com/)_
- _[https://www.halodoc.com](https://www.halodoc.com/)_
- _[https://e-katalog.lkpp.go.id](https://e-katalog.lkpp.go.id/)_



It is recommended to use this API as an exercise to improve your skills.

>---
> _Thank you for using this API for training purposes._
>
>---