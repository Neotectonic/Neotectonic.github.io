---
title: 2022 NEHRP Meeting iDar Trenching

---

{
  "asset": {
    "generator": "Khronos glTF Blender I/O v1.6.16",
    "version": "2.0"
  },
  "scene": 0,
  "scenes": [
    {
      "name": "Scene",
      "nodes": [
        0,
        1,
        2,
        3,
        4,
        5,
        6,
        7,
        8,
        9,
        10,
        11,
        12,
        13
      ]
    }
  ],
  "nodes": [
    {
      "name": "Light",
      "rotation": [
        0.16907575726509094,
        0.7558803558349609,
        -0.27217137813568115,
        0.570947527885437
      ],
      "translation": [
        3.5505871772766113,
        0.3882780075073242,
        6.166833877563477
      ]
    },
    {
      "name": "Camera",
      "rotation": [
        0.6960362195968628,
        0.022752515971660614,
        -0.030500056222081184,
        0.7169976830482483
      ],
      "translation": [
        0.763978123664856,
        0.47723114490509033,
        16.81962776184082
      ]
    },
    {
      "mesh": 0,
      "name": "textured_output",
      "rotation": [
        0.7071068286895752,
        0,
        0,
        0.7071067094802856
      ]
    },
    {
      "name": "Light.001",
      "rotation": [
        0.16907575726509094,
        0.7558803558349609,
        -0.27217137813568115,
        0.570947527885437
      ],
      "translation": [
        -6.227155685424805,
        -0.8543763160705566,
        5.303709983825684
      ]
    },
    {
      "name": "_Contacts"
    },
    {
      "name": "_Faults"
    },
    {
      "name": "_Beds"
    },
    {
      "mesh": 1,
      "name": "Cube",
      "scale": [
        0.4219409227371216,
        0.4219409227371216,
        0.4219409227371216
      ],
      "translation": [
        -6.014124870300293,
        -1.345557689666748,
        -1.1576541662216187
      ]
    },
    {
      "mesh": 2,
      "name": "ScaleText",
      "rotation": [
        0.7071068286895752,
        0,
        0,
        0.7071068286895752
      ],
      "scale": [
        0.5,
        0.5,
        0.5
      ],
      "translation": [
        -6.41675329208374,
        -1.5192359685897827,
        -0.6510775089263916
      ]
    },
    {
      "name": "_Beds.001",
      "translation": [
        0.005544544197618961,
        -0.00006595000741071999,
        0.0010280783753842115
      ]
    },
    {
      "mesh": 3,
      "name": "Beds"
    },
    {
      "name": "_Contacts.001"
    },
    {
      "mesh": 4,
      "name": "Contacts"
    },
    {
      "mesh": 5,
      "name": "Faults"
    }
  ],
  "animations": [
    {
      "channels": [
        {
          "sampler": 0,
          "target": {
            "node": 1,
            "path": "translation"
          }
        },
        {
          "sampler": 1,
          "target": {
            "node": 1,
            "path": "rotation"
          }
        },
        {
          "sampler": 2,
          "target": {
            "node": 1,
            "path": "scale"
          }
        }
      ],
      "name": "CameraAction",
      "samplers": [
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 25
        },
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 26
        },
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 27
        }
      ]
    },
    {
      "channels": [
        {
          "sampler": 0,
          "target": {
            "node": 7,
            "path": "translation"
          }
        },
        {
          "sampler": 1,
          "target": {
            "node": 7,
            "path": "rotation"
          }
        },
        {
          "sampler": 2,
          "target": {
            "node": 7,
            "path": "scale"
          }
        }
      ],
      "name": "CubeAction",
      "samplers": [
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 28
        },
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 29
        },
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 30
        }
      ]
    },
    {
      "channels": [
        {
          "sampler": 0,
          "target": {
            "node": 8,
            "path": "translation"
          }
        },
        {
          "sampler": 1,
          "target": {
            "node": 8,
            "path": "rotation"
          }
        },
        {
          "sampler": 2,
          "target": {
            "node": 8,
            "path": "scale"
          }
        }
      ],
      "name": "TextAction",
      "samplers": [
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 31
        },
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 32
        },
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 33
        }
      ]
    },
    {
      "channels": [
        {
          "sampler": 0,
          "target": {
            "node": 9,
            "path": "translation"
          }
        },
        {
          "sampler": 1,
          "target": {
            "node": 9,
            "path": "rotation"
          }
        },
        {
          "sampler": 2,
          "target": {
            "node": 9,
            "path": "scale"
          }
        }
      ],
      "name": "_Beds.001Action",
      "samplers": [
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 34
        },
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 35
        },
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 36
        }
      ]
    },
    {
      "channels": [
        {
          "sampler": 0,
          "target": {
            "node": 11,
            "path": "translation"
          }
        },
        {
          "sampler": 1,
          "target": {
            "node": 11,
            "path": "rotation"
          }
        },
        {
          "sampler": 2,
          "target": {
            "node": 11,
            "path": "scale"
          }
        }
      ],
      "name": "_Contacts.001Action",
      "samplers": [
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 37
        },
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 38
        },
        {
          "input": 24,
          "interpolation": "STEP",
          "output": 39
        }
      ]
    }
  ],
  "materials": [
    {
      "doubleSided": true,
      "name": "material_0",
      "pbrMetallicRoughness": {
        "baseColorTexture": {
          "index": 0
        },
        "metallicFactor": 0,
        "roughnessFactor": 0.9666666388511658,
        "baseColorFactor": [
          1,
          1,
          1,
          1
        ]
      },
      "emissiveFactor": [
        0,
        0,
        0
      ],
      "alphaMode": "OPAQUE",
      "alphaCutoff": 0.5
    },
    {
      "doubleSided": true,
      "name": "Material.003",
      "pbrMetallicRoughness": {
        "baseColorFactor": [
          0,
          0,
          0,
          1
        ],
        "metallicFactor": 0,
        "roughnessFactor": 0
      },
      "emissiveFactor": [
        0,
        0,
        0
      ],
      "alphaMode": "OPAQUE",
      "alphaCutoff": 0.5
    },
    {
      "doubleSided": true,
      "name": "Material.004",
      "pbrMetallicRoughness": {
        "baseColorFactor": [
          0,
          0,
          0,
          0
        ],
        "metallicFactor": 0,
        "roughnessFactor": 0
      },
      "emissiveFactor": [
        0,
        0,
        0
      ],
      "alphaMode": "OPAQUE",
      "alphaCutoff": 0.5
    },
    {
      "doubleSided": true,
      "name": "Material.005",
      "pbrMetallicRoughness": {
        "baseColorFactor": [
          0,
          0,
          0,
          1
        ],
        "metallicFactor": 0,
        "roughnessFactor": 0
      },
      "emissiveFactor": [
        0,
        0,
        0
      ],
      "alphaMode": "OPAQUE",
      "alphaCutoff": 0.5
    },
    {
      "doubleSided": true,
      "emissiveFactor": [
        1,
        0,
        0.0002649183152243495
      ],
      "name": "Material.006",
      "pbrMetallicRoughness": {
        "baseColorFactor": [
          0.8000000715255737,
          0.0008883798727765679,
          0,
          1
        ],
        "metallicFactor": 0,
        "roughnessFactor": 0
      },
      "alphaMode": "OPAQUE",
      "alphaCutoff": 0.5
    },
    {
      "name": "Default",
      "pbrMetallicRoughness": {
        "baseColorFactor": [
          1,
          1,
          1,
          1
        ],
        "roughnessFactor": 1,
        "metallicFactor": 1
      },
      "emissiveFactor": [
        0,
        0,
        0
      ],
      "doubleSided": false,
      "alphaMode": "OPAQUE",
      "alphaCutoff": 0.5
    }
  ],
  "meshes": [
    {
      "name": "textured_output",
      "primitives": [
        {
          "attributes": {
            "POSITION": 0,
            "NORMAL": 1,
            "TEXCOORD_0": 2
          },
          "indices": 3,
          "material": 0
        }
      ]
    },
    {
      "name": "Cube.001",
      "primitives": [
        {
          "attributes": {
            "POSITION": 4,
            "NORMAL": 5,
            "TEXCOORD_0": 6
          },
          "indices": 7
        }
      ]
    },
    {
      "name": "Text",
      "primitives": [
        {
          "attributes": {
            "POSITION": 8,
            "NORMAL": 9,
            "TEXCOORD_0": 10
          },
          "indices": 11,
          "material": 1
        }
      ]
    },
    {
      "name": "GP_Layer",
      "primitives": [
        {
          "attributes": {
            "POSITION": 12,
            "NORMAL": 13,
            "TEXCOORD_0": 14
          },
          "indices": 15,
          "material": 2
        }
      ]
    },
    {
      "name": "GP_Layer.001",
      "primitives": [
        {
          "attributes": {
            "POSITION": 16,
            "NORMAL": 17,
            "TEXCOORD_0": 18
          },
          "indices": 19,
          "material": 3
        }
      ]
    },
    {
      "name": "GP_Layer.002",
      "primitives": [
        {
          "attributes": {
            "POSITION": 20,
            "NORMAL": 21,
            "TEXCOORD_0": 22
          },
          "indices": 23,
          "material": 4
        }
      ]
    }
  ],
  "textures": [
    {
      "sampler": 0,
      "source": 0
    }
  ],
  "images": [
    {
      "bufferView": 4,
      "mimeType": "image/jpeg",
      "name": "textured_output"
    }
  ],
  "accessors": [
    {
      "bufferView": 0,
      "componentType": 5126,
      "count": 928629,
      "max": [
        5.4070000648498535,
        1.1859999895095825,
        2.865999937057495
      ],
      "min": [
        -6.22599983215332,
        -2.005000114440918,
        -2.802999973297119
      ],
      "type": "VEC3"
    },
    {
      "bufferView": 1,
      "componentType": 5126,
      "count": 928629,
      "type": "VEC3"
    },
    {
      "bufferView": 2,
      "componentType": 5126,
      "count": 928629,
      "type": "VEC2"
    },
    {
      "bufferView": 3,
      "componentType": 5125,
      "count": 955764,
      "type": "SCALAR"
    },
    {
      "bufferView": 5,
      "componentType": 5126,
      "count": 24,
      "max": [
        1,
        1,
        1
      ],
      "min": [
        -1,
        -1,
        -1
      ],
      "type": "VEC3"
    },
    {
      "bufferView": 6,
      "componentType": 5126,
      "count": 24,
      "type": "VEC3"
    },
    {
      "bufferView": 7,
      "componentType": 5126,
      "count": 24,
      "type": "VEC2"
    },
    {
      "bufferView": 8,
      "componentType": 5123,
      "count": 36,
      "type": "SCALAR"
    },
    {
      "bufferView": 9,
      "componentType": 5126,
      "count": 149,
      "max": [
        1.4900000095367432,
        0,
        0
      ],
      "min": [
        0.20200000703334808,
        0,
        -0.6820000410079956
      ],
      "type": "VEC3"
    },
    {
      "bufferView": 10,
      "componentType": 5126,
      "count": 149,
      "type": "VEC3"
    },
    {
      "bufferView": 11,
      "componentType": 5126,
      "count": 149,
      "type": "VEC2"
    },
    {
      "bufferView": 12,
      "componentType": 5123,
      "count": 321,
      "type": "SCALAR"
    },
    {
      "bufferView": 13,
      "componentType": 5126,
      "count": 253244,
      "max": [
        4.970095157623291,
        1.3040649890899658,
        0.829100489616394
      ],
      "min": [
        -5.626606464385986,
        -2.659858465194702,
        -1.274061679840088
      ],
      "type": "VEC3"
    },
    {
      "bufferView": 14,
      "componentType": 5126,
      "count": 253244,
      "type": "VEC3"
    },
    {
      "bufferView": 15,
      "componentType": 5126,
      "count": 253244,
      "type": "VEC2"
    },
    {
      "bufferView": 16,
      "componentType": 5125,
      "count": 379866,
      "type": "SCALAR"
    },
    {
      "bufferView": 17,
      "componentType": 5126,
      "count": 492448,
      "max": [
        5.152721881866455,
        1.78949773311615,
        0.9028218388557434
      ],
      "min": [
        -6.055854797363281,
        -2.785362482070923,
        -1.7718077898025513
      ],
      "type": "VEC3"
    },
    {
      "bufferView": 18,
      "componentType": 5126,
      "count": 492448,
      "type": "VEC3"
    },
    {
      "bufferView": 19,
      "componentType": 5126,
      "count": 492448,
      "type": "VEC2"
    },
    {
      "bufferView": 20,
      "componentType": 5125,
      "count": 738672,
      "type": "SCALAR"
    },
    {
      "bufferView": 21,
      "componentType": 5126,
      "count": 22076,
      "max": [
        2.823359727859497,
        -1.2768208980560303,
        0.6063337326049805
      ],
      "min": [
        0.8845349550247192,
        -2.5695815086364746,
        0.07894931733608246
      ],
      "type": "VEC3"
    },
    {
      "bufferView": 22,
      "componentType": 5126,
      "count": 22076,
      "type": "VEC3"
    },
    {
      "bufferView": 23,
      "componentType": 5126,
      "count": 22076,
      "type": "VEC2"
    },
    {
      "bufferView": 24,
      "componentType": 5123,
      "count": 33114,
      "type": "SCALAR"
    },
    {
      "bufferView": 25,
      "componentType": 5126,
      "count": 1,
      "max": [
        0.041666666666666664
      ],
      "min": [
        0.041666666666666664
      ],
      "type": "SCALAR"
    },
    {
      "bufferView": 26,
      "componentType": 5126,
      "count": 1,
      "type": "VEC3"
    },
    {
      "bufferView": 27,
      "componentType": 5126,
      "count": 1,
      "type": "VEC4"
    },
    {
      "bufferView": 28,
      "componentType": 5126,
      "count": 1,
      "type": "VEC3"
    },
    {
      "bufferView": 29,
      "componentType": 5126,
      "count": 1,
      "type": "VEC3"
    },
    {
      "bufferView": 30,
      "componentType": 5126,
      "count": 1,
      "type": "VEC4"
    },
    {
      "bufferView": 31,
      "componentType": 5126,
      "count": 1,
      "type": "VEC3"
    },
    {
      "bufferView": 32,
      "componentType": 5126,
      "count": 1,
      "type": "VEC3"
    },
    {
      "bufferView": 33,
      "componentType": 5126,
      "count": 1,
      "type": "VEC4"
    },
    {
      "bufferView": 34,
      "componentType": 5126,
      "count": 1,
      "type": "VEC3"
    },
    {
      "bufferView": 35,
      "componentType": 5126,
      "count": 1,
      "type": "VEC3"
    },
    {
      "bufferView": 36,
      "componentType": 5126,
      "count": 1,
      "type": "VEC4"
    },
    {
      "bufferView": 37,
      "componentType": 5126,
      "count": 1,
      "type": "VEC3"
    },
    {
      "bufferView": 38,
      "componentType": 5126,
      "count": 1,
      "type": "VEC3"
    },
    {
      "bufferView": 39,
      "componentType": 5126,
      "count": 1,
      "type": "VEC4"
    },
    {
      "bufferView": 40,
      "componentType": 5126,
      "count": 1,
      "type": "VEC3"
    }
  ],
  "bufferViews": [
    {
      "buffer": 0,
      "byteLength": 11143548,
      "byteOffset": 0
    },
    {
      "buffer": 0,
      "byteLength": 11143548,
      "byteOffset": 11143548
    },
    {
      "buffer": 0,
      "byteLength": 7429032,
      "byteOffset": 22287096
    },
    {
      "buffer": 0,
      "byteLength": 3823056,
      "byteOffset": 29716128
    },
    {
      "buffer": 0,
      "byteLength": 5964661,
      "byteOffset": 33539184
    },
    {
      "buffer": 0,
      "byteLength": 288,
      "byteOffset": 39503848
    },
    {
      "buffer": 0,
      "byteLength": 288,
      "byteOffset": 39504136
    },
    {
      "buffer": 0,
      "byteLength": 192,
      "byteOffset": 39504424
    },
    {
      "buffer": 0,
      "byteLength": 72,
      "byteOffset": 39504616
    },
    {
      "buffer": 0,
      "byteLength": 1788,
      "byteOffset": 39504688
    },
    {
      "buffer": 0,
      "byteLength": 1788,
      "byteOffset": 39506476
    },
    {
      "buffer": 0,
      "byteLength": 1192,
      "byteOffset": 39508264
    },
    {
      "buffer": 0,
      "byteLength": 642,
      "byteOffset": 39509456
    },
    {
      "buffer": 0,
      "byteLength": 3038928,
      "byteOffset": 39510100
    },
    {
      "buffer": 0,
      "byteLength": 3038928,
      "byteOffset": 42549028
    },
    {
      "buffer": 0,
      "byteLength": 2025952,
      "byteOffset": 45587956
    },
    {
      "buffer": 0,
      "byteLength": 1519464,
      "byteOffset": 47613908
    },
    {
      "buffer": 0,
      "byteLength": 5909376,
      "byteOffset": 49133372
    },
    {
      "buffer": 0,
      "byteLength": 5909376,
      "byteOffset": 55042748
    },
    {
      "buffer": 0,
      "byteLength": 3939584,
      "byteOffset": 60952124
    },
    {
      "buffer": 0,
      "byteLength": 2954688,
      "byteOffset": 64891708
    },
    {
      "buffer": 0,
      "byteLength": 264912,
      "byteOffset": 67846396
    },
    {
      "buffer": 0,
      "byteLength": 264912,
      "byteOffset": 68111308
    },
    {
      "buffer": 0,
      "byteLength": 176608,
      "byteOffset": 68376220
    },
    {
      "buffer": 0,
      "byteLength": 66228,
      "byteOffset": 68552828
    },
    {
      "buffer": 0,
      "byteLength": 4,
      "byteOffset": 68619056
    },
    {
      "buffer": 0,
      "byteLength": 12,
      "byteOffset": 68619060
    },
    {
      "buffer": 0,
      "byteLength": 16,
      "byteOffset": 68619072
    },
    {
      "buffer": 0,
      "byteLength": 12,
      "byteOffset": 68619088
    },
    {
      "buffer": 0,
      "byteLength": 12,
      "byteOffset": 68619100
    },
    {
      "buffer": 0,
      "byteLength": 16,
      "byteOffset": 68619112
    },
    {
      "buffer": 0,
      "byteLength": 12,
      "byteOffset": 68619128
    },
    {
      "buffer": 0,
      "byteLength": 12,
      "byteOffset": 68619140
    },
    {
      "buffer": 0,
      "byteLength": 16,
      "byteOffset": 68619152
    },
    {
      "buffer": 0,
      "byteLength": 12,
      "byteOffset": 68619168
    },
    {
      "buffer": 0,
      "byteLength": 12,
      "byteOffset": 68619180
    },
    {
      "buffer": 0,
      "byteLength": 16,
      "byteOffset": 68619192
    },
    {
      "buffer": 0,
      "byteLength": 12,
      "byteOffset": 68619208
    },
    {
      "buffer": 0,
      "byteLength": 12,
      "byteOffset": 68619220
    },
    {
      "buffer": 0,
      "byteLength": 16,
      "byteOffset": 68619232
    },
    {
      "buffer": 0,
      "byteLength": 12,
      "byteOffset": 68619248
    }
  ],
  "samplers": [
    {
      "magFilter": 9729,
      "minFilter": 9987,
      "wrapS": 1000,
      "wrapT": 1000
    }
  ],
  "buffers": [
    {
      "byteLength": 68619260
    }
  ]
}
          
