# E-waste-
Deposition of e-waste for a greener and better earth.
aSkip to content
Why GitHub? 
Enterprise
Explore 
Marketplace
Pricing 
Search

Sign in
Sign up
rahulagnii
/
e-Waste
000
 Code Issues 0 Pull requests 4 Actions Projects 0 Security Insights
Join GitHub today
GitHub is home to over 40 million developers working together to host and review code, manage projects, and build software together.

e-Waste/package-lock.json
@rahulagnii rahulagnii updated
d5758f3 on Mar 2, 2019
8112 lines (8112 sloc)  309 KB
  
{
  "requires": true,
  "lockfileVersion": 1,
  "dependencies": {
    "@babel/code-frame": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/@babel/code-frame/-/code-frame-7.0.0.tgz",
      "integrity": "sha512-OfC2uemaknXr87bdLUkWog7nYuliM9Ij5HUcajsVcMCpQrcLmtxRbVFTIqmcSkSeYRBFBRxs2FiUqFJDLdiebA==",
      "requires": {
        "@babel/highlight": "^7.0.0"
      }
    },
    "@babel/core": {
      "version": "7.3.3",
      "resolved": "https://registry.npmjs.org/@babel/core/-/core-7.3.3.tgz",
      "integrity": "sha512-w445QGI2qd0E0GlSnq6huRZWPMmQGCp5gd5ZWS4hagn0EiwzxD5QMFkpchyusAyVC1n27OKXzQ0/88aVU9n4xQ==",
      "requires": {
        "@babel/code-frame": "^7.0.0",
        "@babel/generator": "^7.3.3",
        "@babel/helpers": "^7.2.0",
        "@babel/parser": "^7.3.3",
        "@babel/template": "^7.2.2",
        "@babel/traverse": "^7.2.2",
        "@babel/types": "^7.3.3",
        "convert-source-map": "^1.1.0",
        "debug": "^4.1.0",
        "json5": "^2.1.0",
        "lodash": "^4.17.11",
        "resolve": "^1.3.2",
        "semver": "^5.4.1",
        "source-map": "^0.5.0"
      },
      "dependencies": {
        "debug": {
          "version": "4.1.1",
          "resolved": "https://registry.npmjs.org/debug/-/debug-4.1.1.tgz",
          "integrity": "sha512-pYAIzeRo8J6KPEaJ0VWOh5Pzkbw/RetuzehGM7QRRX5he4fPHx2rdKMB256ehJCkX+XRQm16eZLqLNS8RSZXZw==",
          "requires": {
            "ms": "^2.1.1"
          }
        },
        "json5": {
          "version": "2.1.0",
          "resolved": "https://registry.npmjs.org/json5/-/json5-2.1.0.tgz",
          "integrity": "sha512-8Mh9h6xViijj36g7Dxi+Y4S6hNGV96vcJZr/SrlHh1LR/pEn/8j/+qIBbs44YKl69Lrfctp4QD+AdWLTMqEZAQ==",
          "requires": {
            "minimist": "^1.2.0"
          }
        },
        "ms": {
          "version": "2.1.1",
          "resolved": "https://registry.npmjs.org/ms/-/ms-2.1.1.tgz",
          "integrity": "sha512-tgp+dl5cGk28utYktBsrFqA7HKgrhgPsg6Z/EfhWI4gl1Hwq8B/GmY/0oXZ6nF8hDVesS/FpnYaD/kOWhYQvyg=="
        }
      }
    },
    "@babel/generator": {
      "version": "7.3.3",
      "resolved": "https://registry.npmjs.org/@babel/generator/-/generator-7.3.3.tgz",
      "integrity": "sha512-aEADYwRRZjJyMnKN7llGIlircxTCofm3dtV5pmY6ob18MSIuipHpA2yZWkPlycwu5HJcx/pADS3zssd8eY7/6A==",
      "requires": {
        "@babel/types": "^7.3.3",
        "jsesc": "^2.5.1",
        "lodash": "^4.17.11",
        "source-map": "^0.5.0",
        "trim-right": "^1.0.1"
      }
    },
    "@babel/helper-annotate-as-pure": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-annotate-as-pure/-/helper-annotate-as-pure-7.0.0.tgz",
      "integrity": "sha512-3UYcJUj9kvSLbLbUIfQTqzcy5VX7GRZ/CCDrnOaZorFFM01aXp1+GJwuFGV4NDDoAS+mOUyHcO6UD/RfqOks3Q==",
      "requires": {
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-builder-binary-assignment-operator-visitor": {
      "version": "7.1.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-builder-binary-assignment-operator-visitor/-/helper-builder-binary-assignment-operator-visitor-7.1.0.tgz",
      "integrity": "sha512-qNSR4jrmJ8M1VMM9tibvyRAHXQs2PmaksQF7c1CGJNipfe3D8p+wgNwgso/P2A2r2mdgBWAXljNWR0QRZAMW8w==",
      "requires": {
        "@babel/helper-explode-assignable-expression": "^7.1.0",
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-builder-react-jsx": {
      "version": "7.3.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-builder-react-jsx/-/helper-builder-react-jsx-7.3.0.tgz",
      "integrity": "sha512-MjA9KgwCuPEkQd9ncSXvSyJ5y+j2sICHyrI0M3L+6fnS4wMSNDc1ARXsbTfbb2cXHn17VisSnU/sHFTCxVxSMw==",
      "requires": {
        "@babel/types": "^7.3.0",
        "esutils": "^2.0.0"
      }
    },
    "@babel/helper-call-delegate": {
      "version": "7.1.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-call-delegate/-/helper-call-delegate-7.1.0.tgz",
      "integrity": "sha512-YEtYZrw3GUK6emQHKthltKNZwszBcHK58Ygcis+gVUrF4/FmTVr5CCqQNSfmvg2y+YDEANyYoaLz/SHsnusCwQ==",
      "requires": {
        "@babel/helper-hoist-variables": "^7.0.0",
        "@babel/traverse": "^7.1.0",
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-create-class-features-plugin": {
      "version": "7.3.2",
      "resolved": "https://registry.npmjs.org/@babel/helper-create-class-features-plugin/-/helper-create-class-features-plugin-7.3.2.tgz",
      "integrity": "sha512-tdW8+V8ceh2US4GsYdNVNoohq5uVwOf9k6krjwW4E1lINcHgttnWcNqgdoessn12dAy8QkbezlbQh2nXISNY+A==",
      "requires": {
        "@babel/helper-function-name": "^7.1.0",
        "@babel/helper-member-expression-to-functions": "^7.0.0",
        "@babel/helper-optimise-call-expression": "^7.0.0",
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/helper-replace-supers": "^7.2.3"
      }
    },
    "@babel/helper-define-map": {
      "version": "7.1.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-define-map/-/helper-define-map-7.1.0.tgz",
      "integrity": "sha512-yPPcW8dc3gZLN+U1mhYV91QU3n5uTbx7DUdf8NnPbjS0RMwBuHi9Xt2MUgppmNz7CJxTBWsGczTiEp1CSOTPRg==",
      "requires": {
        "@babel/helper-function-name": "^7.1.0",
        "@babel/types": "^7.0.0",
        "lodash": "^4.17.10"
      }
    },
    "@babel/helper-explode-assignable-expression": {
      "version": "7.1.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-explode-assignable-expression/-/helper-explode-assignable-expression-7.1.0.tgz",
      "integrity": "sha512-NRQpfHrJ1msCHtKjbzs9YcMmJZOg6mQMmGRB+hbamEdG5PNpaSm95275VD92DvJKuyl0s2sFiDmMZ+EnnvufqA==",
      "requires": {
        "@babel/traverse": "^7.1.0",
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-function-name": {
      "version": "7.1.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-function-name/-/helper-function-name-7.1.0.tgz",
      "integrity": "sha512-A95XEoCpb3TO+KZzJ4S/5uW5fNe26DjBGqf1o9ucyLyCmi1dXq/B3c8iaWTfBk3VvetUxl16e8tIrd5teOCfGw==",
      "requires": {
        "@babel/helper-get-function-arity": "^7.0.0",
        "@babel/template": "^7.1.0",
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-get-function-arity": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-get-function-arity/-/helper-get-function-arity-7.0.0.tgz",
      "integrity": "sha512-r2DbJeg4svYvt3HOS74U4eWKsUAMRH01Z1ds1zx8KNTPtpTL5JAsdFv8BNyOpVqdFhHkkRDIg5B4AsxmkjAlmQ==",
      "requires": {
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-hoist-variables": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-hoist-variables/-/helper-hoist-variables-7.0.0.tgz",
      "integrity": "sha512-Ggv5sldXUeSKsuzLkddtyhyHe2YantsxWKNi7A+7LeD12ExRDWTRk29JCXpaHPAbMaIPZSil7n+lq78WY2VY7w==",
      "requires": {
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-member-expression-to-functions": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-member-expression-to-functions/-/helper-member-expression-to-functions-7.0.0.tgz",
      "integrity": "sha512-avo+lm/QmZlv27Zsi0xEor2fKcqWG56D5ae9dzklpIaY7cQMK5N8VSpaNVPPagiqmy7LrEjK1IWdGMOqPu5csg==",
      "requires": {
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-module-imports": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-module-imports/-/helper-module-imports-7.0.0.tgz",
      "integrity": "sha512-aP/hlLq01DWNEiDg4Jn23i+CXxW/owM4WpDLFUbpjxe4NS3BhLVZQ5i7E0ZrxuQ/vwekIeciyamgB1UIYxxM6A==",
      "requires": {
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-module-transforms": {
      "version": "7.2.2",
      "resolved": "https://registry.npmjs.org/@babel/helper-module-transforms/-/helper-module-transforms-7.2.2.tgz",
      "integrity": "sha512-YRD7I6Wsv+IHuTPkAmAS4HhY0dkPobgLftHp0cRGZSdrRvmZY8rFvae/GVu3bD00qscuvK3WPHB3YdNpBXUqrA==",
      "requires": {
        "@babel/helper-module-imports": "^7.0.0",
        "@babel/helper-simple-access": "^7.1.0",
        "@babel/helper-split-export-declaration": "^7.0.0",
        "@babel/template": "^7.2.2",
        "@babel/types": "^7.2.2",
        "lodash": "^4.17.10"
      }
    },
    "@babel/helper-optimise-call-expression": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-optimise-call-expression/-/helper-optimise-call-expression-7.0.0.tgz",
      "integrity": "sha512-u8nd9NQePYNQV8iPWu/pLLYBqZBa4ZaY1YWRFMuxrid94wKI1QNt67NEZ7GAe5Kc/0LLScbim05xZFWkAdrj9g==",
      "requires": {
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-plugin-utils": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-plugin-utils/-/helper-plugin-utils-7.0.0.tgz",
      "integrity": "sha512-CYAOUCARwExnEixLdB6sDm2dIJ/YgEAKDM1MOeMeZu9Ld/bDgVo8aiWrXwcY7OBh+1Ea2uUcVRcxKk0GJvW7QA=="
    },
    "@babel/helper-regex": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-regex/-/helper-regex-7.0.0.tgz",
      "integrity": "sha512-TR0/N0NDCcUIUEbqV6dCO+LptmmSQFQ7q70lfcEB4URsjD0E1HzicrwUH+ap6BAQ2jhCX9Q4UqZy4wilujWlkg==",
      "requires": {
        "lodash": "^4.17.10"
      }
    },
    "@babel/helper-remap-async-to-generator": {
      "version": "7.1.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-remap-async-to-generator/-/helper-remap-async-to-generator-7.1.0.tgz",
      "integrity": "sha512-3fOK0L+Fdlg8S5al8u/hWE6vhufGSn0bN09xm2LXMy//REAF8kDCrYoOBKYmA8m5Nom+sV9LyLCwrFynA8/slg==",
      "requires": {
        "@babel/helper-annotate-as-pure": "^7.0.0",
        "@babel/helper-wrap-function": "^7.1.0",
        "@babel/template": "^7.1.0",
        "@babel/traverse": "^7.1.0",
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-replace-supers": {
      "version": "7.2.3",
      "resolved": "https://registry.npmjs.org/@babel/helper-replace-supers/-/helper-replace-supers-7.2.3.tgz",
      "integrity": "sha512-GyieIznGUfPXPWu0yLS6U55Mz67AZD9cUk0BfirOWlPrXlBcan9Gz+vHGz+cPfuoweZSnPzPIm67VtQM0OWZbA==",
      "requires": {
        "@babel/helper-member-expression-to-functions": "^7.0.0",
        "@babel/helper-optimise-call-expression": "^7.0.0",
        "@babel/traverse": "^7.2.3",
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-simple-access": {
      "version": "7.1.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-simple-access/-/helper-simple-access-7.1.0.tgz",
      "integrity": "sha512-Vk+78hNjRbsiu49zAPALxTb+JUQCz1aolpd8osOF16BGnLtseD21nbHgLPGUwrXEurZgiCOUmvs3ExTu4F5x6w==",
      "requires": {
        "@babel/template": "^7.1.0",
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-split-export-declaration": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-split-export-declaration/-/helper-split-export-declaration-7.0.0.tgz",
      "integrity": "sha512-MXkOJqva62dfC0w85mEf/LucPPS/1+04nmmRMPEBUB++hiiThQ2zPtX/mEWQ3mtzCEjIJvPY8nuwxXtQeQwUag==",
      "requires": {
        "@babel/types": "^7.0.0"
      }
    },
    "@babel/helper-wrap-function": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-wrap-function/-/helper-wrap-function-7.2.0.tgz",
      "integrity": "sha512-o9fP1BZLLSrYlxYEYyl2aS+Flun5gtjTIG8iln+XuEzQTs0PLagAGSXUcqruJwD5fM48jzIEggCKpIfWTcR7pQ==",
      "requires": {
        "@babel/helper-function-name": "^7.1.0",
        "@babel/template": "^7.1.0",
        "@babel/traverse": "^7.1.0",
        "@babel/types": "^7.2.0"
      }
    },
    "@babel/helpers": {
      "version": "7.3.1",
      "resolved": "https://registry.npmjs.org/@babel/helpers/-/helpers-7.3.1.tgz",
      "integrity": "sha512-Q82R3jKsVpUV99mgX50gOPCWwco9Ec5Iln/8Vyu4osNIOQgSrd9RFrQeUvmvddFNoLwMyOUWU+5ckioEKpDoGA==",
      "requires": {
        "@babel/template": "^7.1.2",
        "@babel/traverse": "^7.1.5",
        "@babel/types": "^7.3.0"
      }
    },
    "@babel/highlight": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/@babel/highlight/-/highlight-7.0.0.tgz",
      "integrity": "sha512-UFMC4ZeFC48Tpvj7C8UgLvtkaUuovQX+5xNWrsIoMG8o2z+XFKjKaN9iVmS84dPwVN00W4wPmqvYoZF3EGAsfw==",
      "requires": {
        "chalk": "^2.0.0",
        "esutils": "^2.0.2",
        "js-tokens": "^4.0.0"
      },
      "dependencies": {
        "chalk": {
          "version": "2.4.2",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-2.4.2.tgz",
          "integrity": "sha512-Mti+f9lpJNcwF4tWV8/OrTTtF1gZi+f8FqlyAdouralcFWFQWF2+NgCHShjkCb+IFBLq9buZwE1xckQU4peSuQ==",
          "requires": {
            "ansi-styles": "^3.2.1",
            "escape-string-regexp": "^1.0.5",
            "supports-color": "^5.3.0"
          }
        },
        "supports-color": {
          "version": "5.5.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-5.5.0.tgz",
          "integrity": "sha512-QjVjwdXIt408MIiAqCX4oUKsgU2EqAGzs2Ppkm4aQYbjm+ZEWEcW4SfFNTr4uMNZma0ey4f5lgLrkB0aX0QMow==",
          "requires": {
            "has-flag": "^3.0.0"
          }
        }
      }
    },
    "@babel/parser": {
      "version": "7.3.3",
      "resolved": "https://registry.npmjs.org/@babel/parser/-/parser-7.3.3.tgz",
      "integrity": "sha512-xsH1CJoln2r74hR+y7cg2B5JCPaTh+Hd+EbBRk9nWGSNspuo6krjhX0Om6RnRQuIvFq8wVXCLKH3kwKDYhanSg=="
    },
    "@babel/plugin-external-helpers": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-external-helpers/-/plugin-external-helpers-7.2.0.tgz",
      "integrity": "sha512-QFmtcCShFkyAsNtdCM3lJPmRe1iB+vPZymlB4LnDIKEBj2yKQLQKtoxXxJ8ePT5fwMl4QGg303p4mB0UsSI2/g==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-proposal-class-properties": {
      "version": "7.3.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-class-properties/-/plugin-proposal-class-properties-7.3.3.tgz",
      "integrity": "sha512-XO9eeU1/UwGPM8L+TjnQCykuVcXqaO5J1bkRPIygqZ/A2L1xVMJ9aZXrY31c0U4H2/LHKL4lbFQLsxktSrc/Ng==",
      "requires": {
        "@babel/helper-create-class-features-plugin": "^7.3.0",
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-proposal-decorators": {
      "version": "7.3.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-decorators/-/plugin-proposal-decorators-7.3.0.tgz",
      "integrity": "sha512-3W/oCUmsO43FmZIqermmq6TKaRSYhmh/vybPfVFwQWdSb8xwki38uAIvknCRzuyHRuYfCYmJzL9or1v0AffPjg==",
      "requires": {
        "@babel/helper-create-class-features-plugin": "^7.3.0",
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/plugin-syntax-decorators": "^7.2.0"
      }
    },
    "@babel/plugin-proposal-export-default-from": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-export-default-from/-/plugin-proposal-export-default-from-7.2.0.tgz",
      "integrity": "sha512-NVfNe7F6nsasG1FnvcFxh2FN0l04ZNe75qTOAVOILWPam0tw9a63RtT/Dab8dPjedZa4fTQaQ83yMMywF9OSug==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/plugin-syntax-export-default-from": "^7.2.0"
      }
    },
    "@babel/plugin-proposal-nullish-coalescing-operator": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-nullish-coalescing-operator/-/plugin-proposal-nullish-coalescing-operator-7.2.0.tgz",
      "integrity": "sha512-QXj/YjFuFJd68oDvoc1e8aqLr2wz7Kofzvp6Ekd/o7MWZl+nZ0/cpStxND+hlZ7DpRWAp7OmuyT2areZ2V3YUA==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/plugin-syntax-nullish-coalescing-operator": "^7.2.0"
      }
    },
    "@babel/plugin-proposal-object-rest-spread": {
      "version": "7.3.2",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-object-rest-spread/-/plugin-proposal-object-rest-spread-7.3.2.tgz",
      "integrity": "sha512-DjeMS+J2+lpANkYLLO+m6GjoTMygYglKmRe6cDTbFv3L9i6mmiE8fe6B8MtCSLZpVXscD5kn7s6SgtHrDoBWoA==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/plugin-syntax-object-rest-spread": "^7.2.0"
      }
    },
    "@babel/plugin-proposal-optional-catch-binding": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-optional-catch-binding/-/plugin-proposal-optional-catch-binding-7.2.0.tgz",
      "integrity": "sha512-mgYj3jCcxug6KUcX4OBoOJz3CMrwRfQELPQ5560F70YQUBZB7uac9fqaWamKR1iWUzGiK2t0ygzjTScZnVz75g==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/plugin-syntax-optional-catch-binding": "^7.2.0"
      }
    },
    "@babel/plugin-proposal-optional-chaining": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-optional-chaining/-/plugin-proposal-optional-chaining-7.2.0.tgz",
      "integrity": "sha512-ea3Q6edZC/55wEBVZAEz42v528VulyO0eir+7uky/sT4XRcdkWJcFi1aPtitTlwUzGnECWJNExWww1SStt+yWw==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/plugin-syntax-optional-chaining": "^7.2.0"
      }
    },
    "@babel/plugin-syntax-decorators": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-decorators/-/plugin-syntax-decorators-7.2.0.tgz",
      "integrity": "sha512-38QdqVoXdHUQfTpZo3rQwqQdWtCn5tMv4uV6r2RMfTqNBuv4ZBhz79SfaQWKTVmxHjeFv/DnXVC/+agHCklYWA==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-syntax-dynamic-import": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-dynamic-import/-/plugin-syntax-dynamic-import-7.2.0.tgz",
      "integrity": "sha512-mVxuJ0YroI/h/tbFTPGZR8cv6ai+STMKNBq0f8hFxsxWjl94qqhsb+wXbpNMDPU3cfR1TIsVFzU3nXyZMqyK4w==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-syntax-export-default-from": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-export-default-from/-/plugin-syntax-export-default-from-7.2.0.tgz",
      "integrity": "sha512-c7nqUnNST97BWPtoe+Ssi+fJukc9P9/JMZ71IOMNQWza2E+Psrd46N6AEvtw6pqK+gt7ChjXyrw4SPDO79f3Lw==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-syntax-flow": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-flow/-/plugin-syntax-flow-7.2.0.tgz",
      "integrity": "sha512-r6YMuZDWLtLlu0kqIim5o/3TNRAlWb073HwT3e2nKf9I8IIvOggPrnILYPsrrKilmn/mYEMCf/Z07w3yQJF6dg==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-syntax-jsx": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-jsx/-/plugin-syntax-jsx-7.2.0.tgz",
      "integrity": "sha512-VyN4QANJkRW6lDBmENzRszvZf3/4AXaj9YR7GwrWeeN9tEBPuXbmDYVU9bYBN0D70zCWVwUy0HWq2553VCb6Hw==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-syntax-nullish-coalescing-operator": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-nullish-coalescing-operator/-/plugin-syntax-nullish-coalescing-operator-7.2.0.tgz",
      "integrity": "sha512-lRCEaKE+LTxDQtgbYajI04ddt6WW0WJq57xqkAZ+s11h4YgfRHhVA/Y2VhfPzzFD4qeLHWg32DMp9HooY4Kqlg==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-syntax-object-rest-spread": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-object-rest-spread/-/plugin-syntax-object-rest-spread-7.2.0.tgz",
      "integrity": "sha512-t0JKGgqk2We+9may3t0xDdmneaXmyxq0xieYcKHxIsrJO64n1OiMWNUtc5gQK1PA0NpdCRrtZp4z+IUaKugrSA==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-syntax-optional-catch-binding": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-optional-catch-binding/-/plugin-syntax-optional-catch-binding-7.2.0.tgz",
      "integrity": "sha512-bDe4xKNhb0LI7IvZHiA13kff0KEfaGX/Hv4lMA9+7TEc63hMNvfKo6ZFpXhKuEp+II/q35Gc4NoMeDZyaUbj9w==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-syntax-optional-chaining": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-optional-chaining/-/plugin-syntax-optional-chaining-7.2.0.tgz",
      "integrity": "sha512-HtGCtvp5Uq/jH/WNUPkK6b7rufnCPLLlDAFN7cmACoIjaOOiXxUt3SswU5loHqrhtqTsa/WoLQ1OQ1AGuZqaWA==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-syntax-typescript": {
      "version": "7.3.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-typescript/-/plugin-syntax-typescript-7.3.3.tgz",
      "integrity": "sha512-dGwbSMA1YhVS8+31CnPR7LB4pcbrzcV99wQzby4uAfrkZPYZlQ7ImwdpzLqi6Z6IL02b8IAL379CaMwo0x5Lag==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-arrow-functions": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-arrow-functions/-/plugin-transform-arrow-functions-7.2.0.tgz",
      "integrity": "sha512-ER77Cax1+8/8jCB9fo4Ud161OZzWN5qawi4GusDuRLcDbDG+bIGYY20zb2dfAFdTRGzrfq2xZPvF0R64EHnimg==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-async-to-generator": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-async-to-generator/-/plugin-transform-async-to-generator-7.2.0.tgz",
      "integrity": "sha512-CEHzg4g5UraReozI9D4fblBYABs7IM6UerAVG7EJVrTLC5keh00aEuLUT+O40+mJCEzaXkYfTCUKIyeDfMOFFQ==",
      "requires": {
        "@babel/helper-module-imports": "^7.0.0",
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/helper-remap-async-to-generator": "^7.1.0"
      }
    },
    "@babel/plugin-transform-block-scoping": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-block-scoping/-/plugin-transform-block-scoping-7.2.0.tgz",
      "integrity": "sha512-vDTgf19ZEV6mx35yiPJe4fS02mPQUUcBNwWQSZFXSzTSbsJFQvHt7DqyS3LK8oOWALFOsJ+8bbqBgkirZteD5Q==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0",
        "lodash": "^4.17.10"
      }
    },
    "@babel/plugin-transform-classes": {
      "version": "7.3.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-classes/-/plugin-transform-classes-7.3.3.tgz",
      "integrity": "sha512-n0CLbsg7KOXsMF4tSTLCApNMoXk0wOPb0DYfsOO1e7SfIb9gOyfbpKI2MZ+AXfqvlfzq2qsflJ1nEns48Caf2w==",
      "requires": {
        "@babel/helper-annotate-as-pure": "^7.0.0",
        "@babel/helper-define-map": "^7.1.0",
        "@babel/helper-function-name": "^7.1.0",
        "@babel/helper-optimise-call-expression": "^7.0.0",
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/helper-replace-supers": "^7.1.0",
        "@babel/helper-split-export-declaration": "^7.0.0",
        "globals": "^11.1.0"
      }
    },
    "@babel/plugin-transform-computed-properties": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-computed-properties/-/plugin-transform-computed-properties-7.2.0.tgz",
      "integrity": "sha512-kP/drqTxY6Xt3NNpKiMomfgkNn4o7+vKxK2DDKcBG9sHj51vHqMBGy8wbDS/J4lMxnqs153/T3+DmCEAkC5cpA==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-destructuring": {
      "version": "7.3.2",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-destructuring/-/plugin-transform-destructuring-7.3.2.tgz",
      "integrity": "sha512-Lrj/u53Ufqxl/sGxyjsJ2XNtNuEjDyjpqdhMNh5aZ+XFOdThL46KBj27Uem4ggoezSYBxKWAil6Hu8HtwqesYw==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-exponentiation-operator": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-exponentiation-operator/-/plugin-transform-exponentiation-operator-7.2.0.tgz",
      "integrity": "sha512-umh4hR6N7mu4Elq9GG8TOu9M0bakvlsREEC+ialrQN6ABS4oDQ69qJv1VtR3uxlKMCQMCvzk7vr17RHKcjx68A==",
      "requires": {
        "@babel/helper-builder-binary-assignment-operator-visitor": "^7.1.0",
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-flow-strip-types": {
      "version": "7.2.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-flow-strip-types/-/plugin-transform-flow-strip-types-7.2.3.tgz",
      "integrity": "sha512-xnt7UIk9GYZRitqCnsVMjQK1O2eKZwFB3CvvHjf5SGx6K6vr/MScCKQDnf1DxRaj501e3pXjti+inbSXX2ZUoQ==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/plugin-syntax-flow": "^7.2.0"
      }
    },
    "@babel/plugin-transform-for-of": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-for-of/-/plugin-transform-for-of-7.2.0.tgz",
      "integrity": "sha512-Kz7Mt0SsV2tQk6jG5bBv5phVbkd0gd27SgYD4hH1aLMJRchM0dzHaXvrWhVZ+WxAlDoAKZ7Uy3jVTW2mKXQ1WQ==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-function-name": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-function-name/-/plugin-transform-function-name-7.2.0.tgz",
      "integrity": "sha512-kWgksow9lHdvBC2Z4mxTsvc7YdY7w/V6B2vy9cTIPtLEE9NhwoWivaxdNM/S37elu5bqlLP/qOY906LukO9lkQ==",
      "requires": {
        "@babel/helper-function-name": "^7.1.0",
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-literals": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-literals/-/plugin-transform-literals-7.2.0.tgz",
      "integrity": "sha512-2ThDhm4lI4oV7fVQ6pNNK+sx+c/GM5/SaML0w/r4ZB7sAneD/piDJtwdKlNckXeyGK7wlwg2E2w33C/Hh+VFCg==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-modules-commonjs": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-modules-commonjs/-/plugin-transform-modules-commonjs-7.2.0.tgz",
      "integrity": "sha512-V6y0uaUQrQPXUrmj+hgnks8va2L0zcZymeU7TtWEgdRLNkceafKXEduv7QzgQAE4lT+suwooG9dC7LFhdRAbVQ==",
      "requires": {
        "@babel/helper-module-transforms": "^7.1.0",
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/helper-simple-access": "^7.1.0"
      }
    },
    "@babel/plugin-transform-object-assign": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-object-assign/-/plugin-transform-object-assign-7.2.0.tgz",
      "integrity": "sha512-nmE55cZBPFgUktbF2OuoZgPRadfxosLOpSgzEPYotKSls9J4pEPcembi8r78RU37Rph6UApCpNmsQA4QMWK9Ng==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-parameters": {
      "version": "7.3.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-parameters/-/plugin-transform-parameters-7.3.3.tgz",
      "integrity": "sha512-IrIP25VvXWu/VlBWTpsjGptpomtIkYrN/3aDp4UKm7xK6UxZY88kcJ1UwETbzHAlwN21MnNfwlar0u8y3KpiXw==",
      "requires": {
        "@babel/helper-call-delegate": "^7.1.0",
        "@babel/helper-get-function-arity": "^7.0.0",
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-react-display-name": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-react-display-name/-/plugin-transform-react-display-name-7.2.0.tgz",
      "integrity": "sha512-Htf/tPa5haZvRMiNSQSFifK12gtr/8vwfr+A9y69uF0QcU77AVu4K7MiHEkTxF7lQoHOL0F9ErqgfNEAKgXj7A==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-react-jsx": {
      "version": "7.3.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-react-jsx/-/plugin-transform-react-jsx-7.3.0.tgz",
      "integrity": "sha512-a/+aRb7R06WcKvQLOu4/TpjKOdvVEKRLWFpKcNuHhiREPgGRB4TQJxq07+EZLS8LFVYpfq1a5lDUnuMdcCpBKg==",
      "requires": {
        "@babel/helper-builder-react-jsx": "^7.3.0",
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/plugin-syntax-jsx": "^7.2.0"
      }
    },
    "@babel/plugin-transform-react-jsx-source": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-react-jsx-source/-/plugin-transform-react-jsx-source-7.2.0.tgz",
      "integrity": "sha512-A32OkKTp4i5U6aE88GwwcuV4HAprUgHcTq0sSafLxjr6AW0QahrCRCjxogkbbcdtpbXkuTOlgpjophCxb6sh5g==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/plugin-syntax-jsx": "^7.2.0"
      }
    },
    "@babel/plugin-transform-regenerator": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-regenerator/-/plugin-transform-regenerator-7.0.0.tgz",
      "integrity": "sha512-sj2qzsEx8KDVv1QuJc/dEfilkg3RRPvPYx/VnKLtItVQRWt1Wqf5eVCOLZm29CiGFfYYsA3VPjfizTCV0S0Dlw==",
      "requires": {
        "regenerator-transform": "^0.13.3"
      }
    },
    "@babel/plugin-transform-runtime": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-runtime/-/plugin-transform-runtime-7.2.0.tgz",
      "integrity": "sha512-jIgkljDdq4RYDnJyQsiWbdvGeei/0MOTtSHKO/rfbd/mXBxNpdlulMx49L0HQ4pug1fXannxoqCI+fYSle9eSw==",
      "requires": {
        "@babel/helper-module-imports": "^7.0.0",
        "@babel/helper-plugin-utils": "^7.0.0",
        "resolve": "^1.8.1",
        "semver": "^5.5.1"
      }
    },
    "@babel/plugin-transform-shorthand-properties": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-shorthand-properties/-/plugin-transform-shorthand-properties-7.2.0.tgz",
      "integrity": "sha512-QP4eUM83ha9zmYtpbnyjTLAGKQritA5XW/iG9cjtuOI8s1RuL/3V6a3DeSHfKutJQ+ayUfeZJPcnCYEQzaPQqg==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-spread": {
      "version": "7.2.2",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-spread/-/plugin-transform-spread-7.2.2.tgz",
      "integrity": "sha512-KWfky/58vubwtS0hLqEnrWJjsMGaOeSBn90Ezn5Jeg9Z8KKHmELbP1yGylMlm5N6TPKeY9A2+UaSYLdxahg01w==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-sticky-regex": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-sticky-regex/-/plugin-transform-sticky-regex-7.2.0.tgz",
      "integrity": "sha512-KKYCoGaRAf+ckH8gEL3JHUaFVyNHKe3ASNsZ+AlktgHevvxGigoIttrEJb8iKN03Q7Eazlv1s6cx2B2cQ3Jabw==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/helper-regex": "^7.0.0"
      }
    },
    "@babel/plugin-transform-template-literals": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-template-literals/-/plugin-transform-template-literals-7.2.0.tgz",
      "integrity": "sha512-FkPix00J9A/XWXv4VoKJBMeSkyY9x/TqIh76wzcdfl57RJJcf8CehQ08uwfhCDNtRQYtHQKBTwKZDEyjE13Lwg==",
      "requires": {
        "@babel/helper-annotate-as-pure": "^7.0.0",
        "@babel/helper-plugin-utils": "^7.0.0"
      }
    },
    "@babel/plugin-transform-typescript": {
      "version": "7.3.2",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-typescript/-/plugin-transform-typescript-7.3.2.tgz",
      "integrity": "sha512-Pvco0x0ZSCnexJnshMfaibQ5hnK8aUHSvjCQhC1JR8eeg+iBwt0AtCO7gWxJ358zZevuf9wPSO5rv+WJcbHPXQ==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/plugin-syntax-typescript": "^7.2.0"
      }
    },
    "@babel/plugin-transform-unicode-regex": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-unicode-regex/-/plugin-transform-unicode-regex-7.2.0.tgz",
      "integrity": "sha512-m48Y0lMhrbXEJnVUaYly29jRXbQ3ksxPrS1Tg8t+MHqzXhtBYAvI51euOBaoAlZLPHsieY9XPVMf80a5x0cPcA==",
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0",
        "@babel/helper-regex": "^7.0.0",
        "regexpu-core": "^4.1.3"
      }
    },
    "@babel/register": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/@babel/register/-/register-7.0.0.tgz",
      "integrity": "sha512-f/+CRmaCe7rVEvcvPvxeA8j5aJhHC3aJie7YuqcMDhUOuyWLA7J/aNrTaHIzoWPEhpHA54mec4Mm8fv8KBlv3g==",
      "requires": {
        "core-js": "^2.5.7",
        "find-cache-dir": "^1.0.0",
        "home-or-tmp": "^3.0.0",
        "lodash": "^4.17.10",
        "mkdirp": "^0.5.1",
        "pirates": "^4.0.0",
        "source-map-support": "^0.5.9"
      },
      "dependencies": {
        "home-or-tmp": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/home-or-tmp/-/home-or-tmp-3.0.0.tgz",
          "integrity": "sha1-V6j+JM8zzdUkhgoVgh3cJchmcfs="
        },
        "source-map": {
          "version": "0.6.1",
          "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.6.1.tgz",
          "integrity": "sha512-UjgapumWlbMhkBgzT7Ykc5YXUT46F0iKu8SGXq0bcwP5dz/h0Plj6enJqjz1Zbq2l5WaqYnrVbwWOWMyF3F47g=="
        },
        "source-map-support": {
          "version": "0.5.10",
          "resolved": "https://registry.npmjs.org/source-map-support/-/source-map-support-0.5.10.tgz",
          "integrity": "sha512-YfQ3tQFTK/yzlGJuX8pTwa4tifQj4QS2Mj7UegOu8jAz59MqIiMGPXxQhVQiIMNzayuUSF/jEuVnfFF5JqybmQ==",
          "requires": {
            "buffer-from": "^1.0.0",
            "source-map": "^0.6.0"
          }
        }
      }
    },
    "@babel/runtime": {
      "version": "7.3.1",
      "resolved": "https://registry.npmjs.org/@babel/runtime/-/runtime-7.3.1.tgz",
      "integrity": "sha512-7jGW8ppV0ant637pIqAcFfQDDH1orEPGJb8aXfUozuCU3QqX7rX4DA8iwrbPrR1hcH0FTTHz47yQnk+bl5xHQA==",
      "requires": {
        "regenerator-runtime": "^0.12.0"
      },
      "dependencies": {
        "regenerator-runtime": {
          "version": "0.12.1",
          "resolved": "https://registry.npmjs.org/regenerator-runtime/-/regenerator-runtime-0.12.1.tgz",
          "integrity": "sha512-odxIc1/vDlo4iZcfXqRYFj0vpXFNoGdKMAUieAlFYO6m/nl5e9KR/beGf41z4a1FI+aQgtjhuaSlDxQ0hmkrHg=="
        }
      }
    },
    "@babel/template": {
      "version": "7.2.2",
      "resolved": "https://registry.npmjs.org/@babel/template/-/template-7.2.2.tgz",
      "integrity": "sha512-zRL0IMM02AUDwghf5LMSSDEz7sBCO2YnNmpg3uWTZj/v1rcG2BmQUvaGU8GhU8BvfMh1k2KIAYZ7Ji9KXPUg7g==",
      "requires": {
        "@babel/code-frame": "^7.0.0",
        "@babel/parser": "^7.2.2",
        "@babel/types": "^7.2.2"
      }
    },
    "@babel/traverse": {
      "version": "7.2.3",
      "resolved": "https://registry.npmjs.org/@babel/traverse/-/traverse-7.2.3.tgz",
      "integrity": "sha512-Z31oUD/fJvEWVR0lNZtfgvVt512ForCTNKYcJBGbPb1QZfve4WGH8Wsy7+Mev33/45fhP/hwQtvgusNdcCMgSw==",
      "requires": {
        "@babel/code-frame": "^7.0.0",
        "@babel/generator": "^7.2.2",
        "@babel/helper-function-name": "^7.1.0",
        "@babel/helper-split-export-declaration": "^7.0.0",
        "@babel/parser": "^7.2.3",
        "@babel/types": "^7.2.2",
        "debug": "^4.1.0",
        "globals": "^11.1.0",
        "lodash": "^4.17.10"
      },
      "dependencies": {
        "debug": {
          "version": "4.1.1",
          "resolved": "https://registry.npmjs.org/debug/-/debug-4.1.1.tgz",
          "integrity": "sha512-pYAIzeRo8J6KPEaJ0VWOh5Pzkbw/RetuzehGM7QRRX5he4fPHx2rdKMB256ehJCkX+XRQm16eZLqLNS8RSZXZw==",
          "requires": {
            "ms": "^2.1.1"
          }
        },
        "ms": {
          "version": "2.1.1",
          "resolved": "https://registry.npmjs.org/ms/-/ms-2.1.1.tgz",
          "integrity": "sha512-tgp+dl5cGk28utYktBsrFqA7HKgrhgPsg6Z/EfhWI4gl1Hwq8B/GmY/0oXZ6nF8hDVesS/FpnYaD/kOWhYQvyg=="
        }
      }
    },
    "@babel/types": {
      "version": "7.3.3",
      "resolved": "https://registry.npmjs.org/@babel/types/-/types-7.3.3.tgz",
      "integrity": "sha512-2tACZ80Wg09UnPg5uGAOUvvInaqLk3l/IAhQzlxLQOIXacr6bMsra5SH6AWw/hIDRCSbCdHP2KzSOD+cT7TzMQ==",
      "requires": {
        "esutils": "^2.0.2",
        "lodash": "^4.17.11",
        "to-fast-properties": "^2.0.0"
      }
    },
    "@expo/vector-icons": {
      "version": "9.0.0",
      "resolved": "https://registry.npmjs.org/@expo/vector-icons/-/vector-icons-9.0.0.tgz",
      "integrity": "sha512-k5ndrW3oueW5jRDLt3o8iXKmiU+CvvCZPewOvxY7eRMivi8hIr6TkW6tMCGE1vS5fwmXffIkIpKGZkSbX7TxwA==",
      "requires": {
        "lodash": "^4.17.4",
        "react-native-vector-icons": "6.0.0"
      },
      "dependencies": {
        "react-native-vector-icons": {
          "version": "6.0.0",
          "resolved": "https://registry.npmjs.org/react-native-vector-icons/-/react-native-vector-icons-6.0.0.tgz",
          "integrity": "sha512-uF3oWb3TV42uXi2apVOZHw9oy9Nr5SXDVwOo1umQWo/yYCrDzXyVfq14DzezgEbJ9jfc/yghBelj0agkXmOKlg==",
          "requires": {
            "lodash": "^4.0.0",
            "prop-types": "^15.6.2",
            "yargs": "^8.0.2"
          }
        },
        "yargs": {
          "version": "8.0.2",
          "resolved": "https://registry.npmjs.org/yargs/-/yargs-8.0.2.tgz",
          "integrity": "sha1-YpmpBVsc78lp/355wdkY3Osiw2A=",
          "requires": {
            "camelcase": "^4.1.0",
            "cliui": "^3.2.0",
            "decamelize": "^1.1.1",
            "get-caller-file": "^1.0.1",
            "os-locale": "^2.0.0",
            "read-pkg-up": "^2.0.0",
            "require-directory": "^2.1.1",
            "require-main-filename": "^1.0.1",
            "set-blocking": "^2.0.0",
            "string-width": "^2.0.0",
            "which-module": "^2.0.0",
            "y18n": "^3.2.1",
            "yargs-parser": "^7.0.0"
          }
        }
      }
    },
    "@expo/websql": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/@expo/websql/-/websql-1.0.1.tgz",
      "integrity": "sha1-//DPnBuqH3D54dZYt8OaQg2bEKk=",
      "requires": {
        "argsarray": "^0.0.1",
        "immediate": "^3.2.2",
        "noop-fn": "^1.0.0",
        "pouchdb-collections": "^1.0.1",
        "tiny-queue": "^0.2.1"
      }
    },
    "@react-navigation/core": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/@react-navigation/core/-/core-3.1.1.tgz",
      "integrity": "sha512-vVPUIpCWO3VKVvE5zYDDR/lOy5hHvRm60rQAHTF19vmt3Jqnbs3qqgYovfUAnTBm0crGLcuIwzOuprRIhC4bfQ==",
      "requires": {
        "create-react-context": "0.2.2",
        "hoist-non-react-statics": "^3.0.1",
        "path-to-regexp": "^1.7.0",
        "query-string": "^6.2.0",
        "react-is": "^16.5.2",
        "react-lifecycles-compat": "^3.0.4"
      },
      "dependencies": {
        "hoist-non-react-statics": {
          "version": "3.3.0",
          "resolved": "https://registry.npmjs.org/hoist-non-react-statics/-/hoist-non-react-statics-3.3.0.tgz",
          "integrity": "sha512-0XsbTXxgiaCDYDIWFcwkmerZPSwywfUqYmwT4jzewKTQSWoE6FCMoUVOeBJWK3E/CrWbxRG3m5GzY4lnIwGRBA==",
          "requires": {
            "react-is": "^16.7.0"
          }
        }
      }
    },
    "@react-navigation/native": {
      "version": "3.1.5",
      "resolved": "https://registry.npmjs.org/@react-navigation/native/-/native-3.1.5.tgz",
      "integrity": "sha512-sDqgNCx98XmiJR4lF8xCMVdADR4NBrx10TkTYbYcwFJ6SJ2LzrfxAW+FwUsESXr5TcSu3/6rGrLGr4rTGjkvRQ==",
      "requires": {
        "hoist-non-react-statics": "^3.0.1",
        "react-native-gesture-handler": "~1.0.14",
        "react-native-safe-area-view": "^0.13.0",
        "react-native-screens": "^1.0.0 || ^1.0.0-alpha"
      },
      "dependencies": {
        "hoist-non-react-statics": {
          "version": "3.3.0",
          "resolved": "https://registry.npmjs.org/hoist-non-react-statics/-/hoist-non-react-statics-3.3.0.tgz",
          "integrity": "sha512-0XsbTXxgiaCDYDIWFcwkmerZPSwywfUqYmwT4jzewKTQSWoE6FCMoUVOeBJWK3E/CrWbxRG3m5GzY4lnIwGRBA==",
          "requires": {
            "react-is": "^16.7.0"
          }
        }
      }
    },
    "@types/fbemitter": {
      "version": "2.0.32",
      "resolved": "https://registry.npmjs.org/@types/fbemitter/-/fbemitter-2.0.32.tgz",
      "integrity": "sha1-jtIE2g9U6cjq7DGx7skeJRMtCCw="
    },
    "@types/invariant": {
      "version": "2.2.29",
      "resolved": "https://registry.npmjs.org/@types/invariant/-/invariant-2.2.29.tgz",
      "integrity": "sha512-lRVw09gOvgviOfeUrKc/pmTiRZ7g7oDOU6OAutyuSHpm1/o2RaBQvRhgK8QEdu+FFuw/wnWb29A/iuxv9i8OpQ=="
    },
    "@types/lodash": {
      "version": "4.14.121",
      "resolved": "https://registry.npmjs.org/@types/lodash/-/lodash-4.14.121.tgz",
      "integrity": "sha512-ORj7IBWj13iYufXt/VXrCNMbUuCTJfhzme5kx9U/UtcIPdJYuvPDUAlHlbNhz/8lKCLy9XGIZnGrqXOtQbPGoQ=="
    },
    "@types/lodash.zipobject": {
      "version": "4.1.5",
      "resolved": "https://registry.npmjs.org/@types/lodash.zipobject/-/lodash.zipobject-4.1.5.tgz",
      "integrity": "sha512-JZDcYsVI3313S7dqrB56ijCvx0nK9xDMochGYLduxCfYQYfcFXqh1Ya2P530rvssEvSRHu0hVNtkSFlkIKfUBg==",
      "requires": {
        "@types/lodash": "*"
      }
    },
    "@types/qs": {
      "version": "6.5.1",
      "resolved": "https://registry.npmjs.org/@types/qs/-/qs-6.5.1.tgz",
      "integrity": "sha512-mNhVdZHdtKHMMxbqzNK3RzkBcN1cux3AvuCYGTvjEIQT2uheH3eCAyYsbMbh2Bq8nXkeOWs1kyDiF7geWRFQ4Q=="
    },
    "@types/uuid-js": {
      "version": "0.7.2",
      "resolved": "https://registry.npmjs.org/@types/uuid-js/-/uuid-js-0.7.2.tgz",
      "integrity": "sha512-9R+mA6mMXkFVQnXEeX5fMQDR2SYND7cafJTqbeMpLhgsL7qr7MF4ZBxWpLexml3lZsBsyAmqVWbOiB0N10m15w=="
    },
    "@types/websql": {
      "version": "0.0.27",
      "resolved": "https://registry.npmjs.org/@types/websql/-/websql-0.0.27.tgz",
      "integrity": "sha1-Yhpman8CAY58u0q6uVaiVzbCfXE="
    },
    "@types/zen-observable": {
      "version": "0.8.0",
      "resolved": "https://registry.npmjs.org/@types/zen-observable/-/zen-observable-0.8.0.tgz",
      "integrity": "sha512-te5lMAWii1uEJ4FwLjzdlbw3+n0FZNOvFXHxQDKeT0dilh7HOzdMzV2TrJVUzq8ep7J4Na8OUYPRLSQkJHAlrg=="
    },
    "absolute-path": {
      "version": "0.0.0",
      "resolved": "https://registry.npmjs.org/absolute-path/-/absolute-path-0.0.0.tgz",
      "integrity": "sha1-p4di+9rftSl76ZsV01p4Wy8JW/c="
    },
    "accepts": {
      "version": "1.3.5",
      "resolved": "https://registry.npmjs.org/accepts/-/accepts-1.3.5.tgz",
      "integrity": "sha1-63d99gEXI6OxTopywIBcjoZ0a9I=",
      "requires": {
        "mime-types": "~2.1.18",
        "negotiator": "0.6.1"
      }
    },
    "ajv": {
      "version": "6.9.1",
      "resolved": "https://registry.npmjs.org/ajv/-/ajv-6.9.1.tgz",
      "integrity": "sha512-XDN92U311aINL77ieWHmqCcNlwjoP5cHXDxIxbf2MaPYuCXOHS7gHH8jktxeK5omgd52XbSTX6a4Piwd1pQmzA==",
      "requires": {
        "fast-deep-equal": "^2.0.1",
        "fast-json-stable-stringify": "^2.0.0",
        "json-schema-traverse": "^0.4.1",
        "uri-js": "^4.2.2"
      }
    },
    "ajv-errors": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/ajv-errors/-/ajv-errors-1.0.1.tgz",
      "integrity": "sha512-DCRfO/4nQ+89p/RK43i8Ezd41EqdGIU4ld7nGF8OQ14oc/we5rEntLCUa7+jrn3nn83BosfwZA0wb4pon2o8iQ=="
    },
    "ajv-keywords": {
      "version": "3.4.0",
      "resolved": "https://registry.npmjs.org/ajv-keywords/-/ajv-keywords-3.4.0.tgz",
      "integrity": "sha512-aUjdRFISbuFOl0EIZc+9e4FfZp0bDZgAdOOf30bJmw8VM9v84SHyVyxDfbWxpGYbdZD/9XoKxfHVNmxPkhwyGw=="
    },
    "ansi": {
      "version": "0.3.1",
      "resolved": "https://registry.npmjs.org/ansi/-/ansi-0.3.1.tgz",
      "integrity": "sha1-DELU+xcWDVqa8eSEus4cZpIsGyE="
    },
    "ansi-colors": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/ansi-colors/-/ansi-colors-1.1.0.tgz",
      "integrity": "sha512-SFKX67auSNoVR38N3L+nvsPjOE0bybKTYbkf5tRvushrAPQ9V75huw0ZxBkKVeRU9kqH3d6HA4xTckbwZ4ixmA==",
      "requires": {
        "ansi-wrap": "^0.1.0"
      }
    },
    "ansi-cyan": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/ansi-cyan/-/ansi-cyan-0.1.1.tgz",
      "integrity": "sha1-U4rlKK+JgvKK4w2G8vF0VtJgmHM=",
      "requires": {
        "ansi-wrap": "0.1.0"
      }
    },
    "ansi-escapes": {
      "version": "3.2.0",
      "resolved": "https://registry.npmjs.org/ansi-escapes/-/ansi-escapes-3.2.0.tgz",
      "integrity": "sha512-cBhpre4ma+U0T1oM5fXg7Dy1Jw7zzwv7lt/GoCpr+hDQJoYnKVPLL4dCvSEFMmQurOQvSrwT7SL/DAlhBI97RQ=="
    },
    "ansi-gray": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/ansi-gray/-/ansi-gray-0.1.1.tgz",
      "integrity": "sha1-KWLPVOyXksSFEKPetSRDaGHvclE=",
      "requires": {
        "ansi-wrap": "0.1.0"
      }
    },
    "ansi-red": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/ansi-red/-/ansi-red-0.1.1.tgz",
      "integrity": "sha1-jGOPnRCAgAo1PJwoyKgcpHBdlGw=",
      "requires": {
        "ansi-wrap": "0.1.0"
      }
    },
    "ansi-regex": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-2.1.1.tgz",
      "integrity": "sha1-w7M6te42DYbg5ijwRorn7yfWVN8="
    },
    "ansi-styles": {
      "version": "3.2.1",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-3.2.1.tgz",
      "integrity": "sha512-VT0ZI6kZRdTh8YyJw3SMbYm/u+NqfsAxEpWO0Pf9sq8/e94WxxOpPKx9FR1FlyCtOVDNOQ+8ntlqFxiRc+r5qA==",
      "requires": {
        "color-convert": "^1.9.0"
      }
    },
    "ansi-wrap": {
      "version": "0.1.0",
      "resolved": "https://registry.npmjs.org/ansi-wrap/-/ansi-wrap-0.1.0.tgz",
      "integrity": "sha1-qCJQ3bABXponyoLoLqYDu/pF768="
    },
    "anymatch": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/anymatch/-/anymatch-2.0.0.tgz",
      "integrity": "sha512-5teOsQWABXHHBFP9y3skS5P3d/WfWXpv3FUpy+LorMrNYaT9pI4oLMQX7jzQ2KklNpGpWHzdCXTDT2Y3XGlZBw==",
      "requires": {
        "micromatch": "^3.1.4",
        "normalize-path": "^2.1.1"
      },
      "dependencies": {
        "arr-diff": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/arr-diff/-/arr-diff-4.0.0.tgz",
          "integrity": "sha1-1kYQdP6/7HHn4VI1dhoyml3HxSA="
        },
        "array-unique": {
          "version": "0.3.2",
          "resolved": "https://registry.npmjs.org/array-unique/-/array-unique-0.3.2.tgz",
          "integrity": "sha1-qJS3XUvE9s1nnvMkSp/Y9Gri1Cg="
        },
        "braces": {
          "version": "2.3.2",
          "resolved": "https://registry.npmjs.org/braces/-/braces-2.3.2.tgz",
          "integrity": "sha512-aNdbnj9P8PjdXU4ybaWLK2IF3jc/EoDYbC7AazW6to3TRsfXxscC9UXOB5iDiEQrkyIbWp2SLQda4+QAa7nc3w==",
          "requires": {
            "arr-flatten": "^1.1.0",
            "array-unique": "^0.3.2",
            "extend-shallow": "^2.0.1",
            "fill-range": "^4.0.0",
            "isobject": "^3.0.1",
            "repeat-element": "^1.1.2",
            "snapdragon": "^0.8.1",
            "snapdragon-node": "^2.0.1",
            "split-string": "^3.0.2",
            "to-regex": "^3.0.1"
          },
          "dependencies": {
            "extend-shallow": {
              "version": "2.0.1",
              "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
              "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
              "requires": {
                "is-extendable": "^0.1.0"
              }
            }
          }
        },
        "expand-brackets": {
          "version": "2.1.4",
          "resolved": "https://registry.npmjs.org/expand-brackets/-/expand-brackets-2.1.4.tgz",
          "integrity": "sha1-t3c14xXOMPa27/D4OwQVGiJEliI=",
          "requires": {
            "debug": "^2.3.3",
            "define-property": "^0.2.5",
            "extend-shallow": "^2.0.1",
            "posix-character-classes": "^0.1.0",
            "regex-not": "^1.0.0",
            "snapdragon": "^0.8.1",
            "to-regex": "^3.0.1"
          },
          "dependencies": {
            "define-property": {
              "version": "0.2.5",
              "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
              "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
              "requires": {
                "is-descriptor": "^0.1.0"
              }
            },
            "extend-shallow": {
              "version": "2.0.1",
              "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
              "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
              "requires": {
                "is-extendable": "^0.1.0"
              }
            },
            "is-accessor-descriptor": {
              "version": "0.1.6",
              "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-0.1.6.tgz",
              "integrity": "sha1-qeEss66Nh2cn7u84Q/igiXtcmNY=",
              "requires": {
                "kind-of": "^3.0.2"
              },
              "dependencies": {
                "kind-of": {
                  "version": "3.2.2",
                  "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
                  "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
                  "requires": {
                    "is-buffer": "^1.1.5"
                  }
                }
              }
            },
            "is-data-descriptor": {
              "version": "0.1.4",
              "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-0.1.4.tgz",
              "integrity": "sha1-C17mSDiOLIYCgueT8YVv7D8wG1Y=",
              "requires": {
                "kind-of": "^3.0.2"
              },
              "dependencies": {
                "kind-of": {
                  "version": "3.2.2",
                  "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
                  "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
                  "requires": {
                    "is-buffer": "^1.1.5"
                  }
                }
              }
            },
            "is-descriptor": {
              "version": "0.1.6",
              "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-0.1.6.tgz",
              "integrity": "sha512-avDYr0SB3DwO9zsMov0gKCESFYqCnE4hq/4z3TdUlukEy5t9C0YRq7HLrsN52NAcqXKaepeCD0n+B0arnVG3Hg==",
              "requires": {
                "is-accessor-descriptor": "^0.1.6",
                "is-data-descriptor": "^0.1.4",
                "kind-of": "^5.0.0"
              }
            },
            "kind-of": {
              "version": "5.1.0",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-5.1.0.tgz",
              "integrity": "sha512-NGEErnH6F2vUuXDh+OlbcKW7/wOcfdRHaZ7VWtqCztfHri/++YKmP51OdWeGPuqCOba6kk2OTe5d02VmTB80Pw=="
            }
          }
        },
        "extend-shallow": {
          "version": "3.0.2",
          "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-3.0.2.tgz",
          "integrity": "sha1-Jqcarwc7OfshJxcnRhMcJwQCjbg=",
          "requires": {
            "assign-symbols": "^1.0.0",
            "is-extendable": "^1.0.1"
          },
          "dependencies": {
            "is-extendable": {
              "version": "1.0.1",
              "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-1.0.1.tgz",
              "integrity": "sha512-arnXMxT1hhoKo9k1LZdmlNyJdDDfy2v0fXjFlmok4+i8ul/6WlbVge9bhM74OpNPQPMGUToDtz+KXa1PneJxOA==",
              "requires": {
                "is-plain-object": "^2.0.4"
              }
            }
          }
        },
        "extglob": {
          "version": "2.0.4",
          "resolved": "https://registry.npmjs.org/extglob/-/extglob-2.0.4.tgz",
          "integrity": "sha512-Nmb6QXkELsuBr24CJSkilo6UHHgbekK5UiZgfE6UHD3Eb27YC6oD+bhcT+tJ6cl8dmsgdQxnWlcry8ksBIBLpw==",
          "requires": {
            "array-unique": "^0.3.2",
            "define-property": "^1.0.0",
            "expand-brackets": "^2.1.4",
            "extend-shallow": "^2.0.1",
            "fragment-cache": "^0.2.1",
            "regex-not": "^1.0.0",
            "snapdragon": "^0.8.1",
            "to-regex": "^3.0.1"
          },
          "dependencies": {
            "define-property": {
              "version": "1.0.0",
              "resolved": "https://registry.npmjs.org/define-property/-/define-property-1.0.0.tgz",
              "integrity": "sha1-dp66rz9KY6rTr56NMEybvnm/sOY=",
              "requires": {
                "is-descriptor": "^1.0.0"
              }
            },
            "extend-shallow": {
              "version": "2.0.1",
              "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
              "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
              "requires": {
                "is-extendable": "^0.1.0"
              }
            }
          }
        },
        "fill-range": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/fill-range/-/fill-range-4.0.0.tgz",
          "integrity": "sha1-1USBHUKPmOsGpj3EAtJAPDKMOPc=",
          "requires": {
            "extend-shallow": "^2.0.1",
            "is-number": "^3.0.0",
            "repeat-string": "^1.6.1",
            "to-regex-range": "^2.1.0"
          },
          "dependencies": {
            "extend-shallow": {
              "version": "2.0.1",
              "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
              "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
              "requires": {
                "is-extendable": "^0.1.0"
              }
            }
          }
        },
        "is-accessor-descriptor": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-1.0.0.tgz",
          "integrity": "sha512-m5hnHTkcVsPfqx3AKlyttIPb7J+XykHvJP2B9bZDjlhLIoEq4XoK64Vg7boZlVWYK6LUY94dYPEE7Lh0ZkZKcQ==",
          "requires": {
            "kind-of": "^6.0.0"
          }
        },
        "is-data-descriptor": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-1.0.0.tgz",
          "integrity": "sha512-jbRXy1FmtAoCjQkVmIVYwuuqDFUbaOeDjmed1tOGPrsMhtJA4rD9tkgA0F1qJ3gRFRXcHYVkdeaP50Q5rE/jLQ==",
          "requires": {
            "kind-of": "^6.0.0"
          }
        },
        "is-descriptor": {
          "version": "1.0.2",
          "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-1.0.2.tgz",
          "integrity": "sha512-2eis5WqQGV7peooDyLmNEPUrps9+SXX5c9pL3xEB+4e9HnGuDa7mB7kHxHw4CbqS9k1T2hOH3miL8n8WtiYVtg==",
          "requires": {
            "is-accessor-descriptor": "^1.0.0",
            "is-data-descriptor": "^1.0.0",
            "kind-of": "^6.0.2"
          }
        },
        "is-number": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/is-number/-/is-number-3.0.0.tgz",
          "integrity": "sha1-JP1iAaR4LPUFYcgQJ2r8fRLXEZU=",
          "requires": {
            "kind-of": "^3.0.2"
          },
          "dependencies": {
            "kind-of": {
              "version": "3.2.2",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
              "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
              "requires": {
                "is-buffer": "^1.1.5"
              }
            }
          }
        },
        "isobject": {
          "version": "3.0.1",
          "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
          "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8="
        },
        "kind-of": {
          "version": "6.0.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-6.0.2.tgz",
          "integrity": "sha512-s5kLOcnH0XqDO+FvuaLX8DDjZ18CGFk7VygH40QoKPUQhW4e2rvM0rwUq0t8IQDOwYSeLK01U90OjzBTme2QqA=="
        },
        "micromatch": {
          "version": "3.1.10",
          "resolved": "https://registry.npmjs.org/micromatch/-/micromatch-3.1.10.tgz",
          "integrity": "sha512-MWikgl9n9M3w+bpsY3He8L+w9eF9338xRl8IAO5viDizwSzziFEyUzo2xrrloB64ADbTf8uA8vRqqttDTOmccg==",
          "requires": {
            "arr-diff": "^4.0.0",
            "array-unique": "^0.3.2",
            "braces": "^2.3.1",
            "define-property": "^2.0.2",
            "extend-shallow": "^3.0.2",
            "extglob": "^2.0.4",
            "fragment-cache": "^0.2.1",
            "kind-of": "^6.0.2",
            "nanomatch": "^1.2.9",
            "object.pick": "^1.3.0",
            "regex-not": "^1.0.0",
            "snapdragon": "^0.8.1",
            "to-regex": "^3.0.2"
          }
        }
      }
    },
    "apollo-boost": {
      "version": "0.3.1",
      "resolved": "https://registry.npmjs.org/apollo-boost/-/apollo-boost-0.3.1.tgz",
      "integrity": "sha512-VdXcTMxLBeNvANW/FtiarEkrRr/cepYKG6wTAURdy8CS33WYpEHtIg9S8tAjxwVzIECpE4lWyDKyPLoESJ072Q==",
      "requires": {
        "apollo-cache": "^1.2.1",
        "apollo-cache-inmemory": "^1.5.1",
        "apollo-client": "^2.5.1",
        "apollo-link": "^1.0.6",
        "apollo-link-error": "^1.0.3",
        "apollo-link-http": "^1.3.1",
        "graphql-tag": "^2.4.2",
        "ts-invariant": "^0.2.1",
        "tslib": "^1.9.3"
      }
    },
    "apollo-cache": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/apollo-cache/-/apollo-cache-1.2.1.tgz",
      "integrity": "sha512-nzFmep/oKlbzUuDyz6fS6aYhRmfpcHWqNkkA9Bbxwk18RD6LXC4eZkuE0gXRX0IibVBHNjYVK+Szi0Yied4SpQ==",
      "requires": {
        "apollo-utilities": "^1.2.1",
        "tslib": "^1.9.3"
      }
    },
    "apollo-cache-inmemory": {
      "version": "1.5.1",
      "resolved": "https://registry.npmjs.org/apollo-cache-inmemory/-/apollo-cache-inmemory-1.5.1.tgz",
      "integrity": "sha512-D3bdpPmWfaKQkWy8lfwUg+K8OBITo3sx0BHLs1B/9vIdOIZ7JNCKq3EUcAgAfInomJUdN0QG1yOfi8M8hxkN1g==",
      "requires": {
        "apollo-cache": "^1.2.1",
        "apollo-utilities": "^1.2.1",
        "optimism": "^0.6.9",
        "ts-invariant": "^0.2.1",
        "tslib": "^1.9.3"
      }
    },
    "apollo-client": {
      "version": "2.5.1",
      "resolved": "https://registry.npmjs.org/apollo-client/-/apollo-client-2.5.1.tgz",
      "integrity": "sha512-MNcQKiqLHdGmNJ0rZ0NXaHrToXapJgS/5kPk0FygXt+/FmDCdzqcujI7OPxEC6e9Yw5S/8dIvOXcRNuOMElHkA==",
      "requires": {
        "@types/zen-observable": "^0.8.0",
        "apollo-cache": "1.2.1",
        "apollo-link": "^1.0.0",
        "apollo-link-dedup": "^1.0.0",
        "apollo-utilities": "1.2.1",
        "symbol-observable": "^1.0.2",
        "ts-invariant": "^0.2.1",
        "tslib": "^1.9.3",
        "zen-observable": "^0.8.0"
      }
    },
    "apollo-link": {
      "version": "1.2.8",
      "resolved": "https://registry.npmjs.org/apollo-link/-/apollo-link-1.2.8.tgz",
      "integrity": "sha512-lfzGRxhK9RmiH3HPFi7TIEBhhDY9M5a2ZDnllcfy5QDk7cCQHQ1WQArcw1FK0g1B+mV4Kl72DSrlvZHZJEolrA==",
      "requires": {
        "zen-observable-ts": "^0.8.15"
      }
    },
    "apollo-link-dedup": {
      "version": "1.0.15",
      "resolved": "https://registry.npmjs.org/apollo-link-dedup/-/apollo-link-dedup-1.0.15.tgz",
      "integrity": "sha512-14/+Tg7ogcYVrvZa8C7uBQIvX2B/dCKSnojI41yDYGp/t2eWD5ITCWdgjhciXpi0Ij6z+NRyMEebACz3EOwm4w==",
      "requires": {
        "apollo-link": "^1.2.8"
      }
    },
    "apollo-link-error": {
      "version": "1.1.7",
      "resolved": "https://registry.npmjs.org/apollo-link-error/-/apollo-link-error-1.1.7.tgz",
      "integrity": "sha512-olPTKr3yFoavFHSXSLqC5QSWrRACN8TK3+E0pVL8uVR0zILJflUSCRb8HizKQmxZWtr9yM+D2gRLu9mStI8qTA==",
      "requires": {
        "apollo-link": "^1.2.8",
        "apollo-link-http-common": "^0.2.10"
      }
    },
    "apollo-link-http": {
      "version": "1.5.11",
      "resolved": "https://registry.npmjs.org/apollo-link-http/-/apollo-link-http-1.5.11.tgz",
      "integrity": "sha512-wDG+I9UmpfaZRPIvTYBgkvqiCgmz6yWgvuzW/S24Q4r4Xrfe6sLpg2FmarhtdP+hdN+IXTLbFNCZ+Trgfpifow==",
      "requires": {
        "apollo-link": "^1.2.8",
        "apollo-link-http-common": "^0.2.10"
      }
    },
    "apollo-link-http-common": {
      "version": "0.2.10",
      "resolved": "https://registry.npmjs.org/apollo-link-http-common/-/apollo-link-http-common-0.2.10.tgz",
      "integrity": "sha512-KY9nhpAurw3z48OIYV0sCZFXrzWp/wjECsveK+Q9GUhhSe1kEbbUjFfmi+qigg+iELgdp5V8ioRJhinl1vPojw==",
      "requires": {
        "apollo-link": "^1.2.8"
      }
    },
    "apollo-utilities": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/apollo-utilities/-/apollo-utilities-1.2.1.tgz",
      "integrity": "sha512-Zv8Udp9XTSFiN8oyXOjf6PMHepD4yxxReLsl6dPUy5Ths7jti3nmlBzZUOxuTWRwZn0MoclqL7RQ5UEJN8MAxg==",
      "requires": {
        "fast-json-stable-stringify": "^2.0.0",
        "ts-invariant": "^0.2.1",
        "tslib": "^1.9.3"
      }
    },
    "are-we-there-yet": {
      "version": "1.1.5",
      "resolved": "https://registry.npmjs.org/are-we-there-yet/-/are-we-there-yet-1.1.5.tgz",
      "integrity": "sha512-5hYdAkZlcG8tOLujVDTgCT+uPX0VnpAH28gWsLfzpXYm7wP6mp5Q/gYyR7YQ0cKVJcXJnl3j2kpBan13PtQf6w==",
      "requires": {
        "delegates": "^1.0.0",
        "readable-stream": "^2.0.6"
      }
    },
    "argparse": {
      "version": "1.0.10",
      "resolved": "https://registry.npmjs.org/argparse/-/argparse-1.0.10.tgz",
      "integrity": "sha512-o5Roy6tNG4SL/FOkCAN6RzjiakZS25RLYFrcMttJqbdd8BWrnA+fGz57iN5Pb06pvBGvl5gQ0B48dJlslXvoTg==",
      "requires": {
        "sprintf-js": "~1.0.2"
      }
    },
    "argsarray": {
      "version": "0.0.1",
      "resolved": "https://registry.npmjs.org/argsarray/-/argsarray-0.0.1.tgz",
      "integrity": "sha1-bnIHtOzbObCviDA/pa4ivajfYcs="
    },
    "arr-diff": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/arr-diff/-/arr-diff-1.1.0.tgz",
      "integrity": "sha1-aHwydYFjWI/vfeezb6vklesaOZo=",
      "requires": {
        "arr-flatten": "^1.0.1",
        "array-slice": "^0.2.3"
      }
    },
    "arr-flatten": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/arr-flatten/-/arr-flatten-1.1.0.tgz",
      "integrity": "sha512-L3hKV5R/p5o81R7O02IGnwpDmkp6E982XhtbuwSe3O4qOtMMMtodicASA1Cny2U+aCXcNpml+m4dPsvsJ3jatg=="
    },
    "arr-union": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/arr-union/-/arr-union-2.1.0.tgz",
      "integrity": "sha1-IPnqtexw9cfSFbEHexw5Fh0pLH0="
    },
    "array-filter": {
      "version": "0.0.1",
      "resolved": "https://registry.npmjs.org/array-filter/-/array-filter-0.0.1.tgz",
      "integrity": "sha1-fajPLiZijtcygDWB/SH2fKzS7uw="
    },
    "array-map": {
      "version": "0.0.0",
      "resolved": "https://registry.npmjs.org/array-map/-/array-map-0.0.0.tgz",
      "integrity": "sha1-iKK6tz0c97zVwbEYoAP2b2ZfpmI="
    },
    "array-reduce": {
      "version": "0.0.0",
      "resolved": "https://registry.npmjs.org/array-reduce/-/array-reduce-0.0.0.tgz",
      "integrity": "sha1-FziZ0//Rx9k4PkR5Ul2+J4yrXys="
    },
    "array-slice": {
      "version": "0.2.3",
      "resolved": "https://registry.npmjs.org/array-slice/-/array-slice-0.2.3.tgz",
      "integrity": "sha1-3Tz7gO15c6dRF82sabC5nshhhvU="
    },
    "array-unique": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/array-unique/-/array-unique-0.2.1.tgz",
      "integrity": "sha1-odl8yvy8JiXMcPrc6zalDFiwGlM="
    },
    "art": {
      "version": "0.10.3",
      "resolved": "https://registry.npmjs.org/art/-/art-0.10.3.tgz",
      "integrity": "sha512-HXwbdofRTiJT6qZX/FnchtldzJjS3vkLJxQilc3Xj+ma2MXjY4UAyQ0ls1XZYVnDvVIBiFZbC6QsvtW86TD6tQ=="
    },
    "asap": {
      "version": "2.0.6",
      "resolved": "https://registry.npmjs.org/asap/-/asap-2.0.6.tgz",
      "integrity": "sha1-5QNHYR1+aQlDIIu9r+vLwvuGbUY="
    },
    "assign-symbols": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/assign-symbols/-/assign-symbols-1.0.0.tgz",
      "integrity": "sha1-WWZ/QfrdTyDMvCu5a41Pf3jsA2c="
    },
    "async": {
      "version": "2.6.2",
      "resolved": "https://registry.npmjs.org/async/-/async-2.6.2.tgz",
      "integrity": "sha512-H1qVYh1MYhEEFLsP97cVKqCGo7KfCyTt6uEWqsTBr9SO84oK9Uwbyd/yCW+6rKJLHksBNUVWZDAjfS+Ccx0Bbg==",
      "requires": {
        "lodash": "^4.17.11"
      }
    },
    "async-limiter": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/async-limiter/-/async-limiter-1.0.0.tgz",
      "integrity": "sha512-jp/uFnooOiO+L211eZOoSyzpOITMXx1rBITauYykG3BRYPu8h0UcxsPNB04RR5vo4Tyz3+ay17tR6JVf9qzYWg=="
    },
    "atob": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/atob/-/atob-2.1.2.tgz",
      "integrity": "sha512-Wm6ukoaOGJi/73p/cl2GvLjTI5JM1k/O14isD73YML8StrH/7/lRFgmg8nICZgD3bZZvjwCGxtMOD3wWNAu8cg=="
    },
    "babel-code-frame": {
      "version": "6.26.0",
      "resolved": "https://registry.npmjs.org/babel-code-frame/-/babel-code-frame-6.26.0.tgz",
      "integrity": "sha1-Y/1D99weO7fONZR9uP42mj9Yx0s=",
      "requires": {
        "chalk": "^1.1.3",
        "esutils": "^2.0.2",
        "js-tokens": "^3.0.2"
      },
      "dependencies": {
        "js-tokens": {
          "version": "3.0.2",
          "resolved": "https://registry.npmjs.org/js-tokens/-/js-tokens-3.0.2.tgz",
          "integrity": "sha1-mGbfOVECEw449/mWvOtlRDIJwls="
        }
      }
    },
    "babel-core": {
      "version": "6.26.3",
      "resolved": "https://registry.npmjs.org/babel-core/-/babel-core-6.26.3.tgz",
      "integrity": "sha512-6jyFLuDmeidKmUEb3NM+/yawG0M2bDZ9Z1qbZP59cyHLz8kYGKYwpJP0UwUKKUiTRNvxfLesJnTedqczP7cTDA==",
      "requires": {
        "babel-code-frame": "^6.26.0",
        "babel-generator": "^6.26.0",
        "babel-helpers": "^6.24.1",
        "babel-messages": "^6.23.0",
        "babel-register": "^6.26.0",
        "babel-runtime": "^6.26.0",
        "babel-template": "^6.26.0",
        "babel-traverse": "^6.26.0",
        "babel-types": "^6.26.0",
        "babylon": "^6.18.0",
        "convert-source-map": "^1.5.1",
        "debug": "^2.6.9",
        "json5": "^0.5.1",
        "lodash": "^4.17.4",
        "minimatch": "^3.0.4",
        "path-is-absolute": "^1.0.1",
        "private": "^0.1.8",
        "slash": "^1.0.0",
        "source-map": "^0.5.7"
      }
    },
    "babel-generator": {
      "version": "6.26.1",
      "resolved": "https://registry.npmjs.org/babel-generator/-/babel-generator-6.26.1.tgz",
      "integrity": "sha512-HyfwY6ApZj7BYTcJURpM5tznulaBvyio7/0d4zFOeMPUmfxkCjHocCuoLa2SAGzBI8AREcH3eP3758F672DppA==",
      "requires": {
        "babel-messages": "^6.23.0",
        "babel-runtime": "^6.26.0",
        "babel-types": "^6.26.0",
        "detect-indent": "^4.0.0",
        "jsesc": "^1.3.0",
        "lodash": "^4.17.4",
        "source-map": "^0.5.7",
        "trim-right": "^1.0.1"
      },
      "dependencies": {
        "jsesc": {
          "version": "1.3.0",
          "resolved": "https://registry.npmjs.org/jsesc/-/jsesc-1.3.0.tgz",
          "integrity": "sha1-RsP+yMGJKxKwgz25vHYiF226s0s="
        }
      }
    },
    "babel-helper-builder-react-jsx": {
      "version": "6.26.0",
      "resolved": "https://registry.npmjs.org/babel-helper-builder-react-jsx/-/babel-helper-builder-react-jsx-6.26.0.tgz",
      "integrity": "sha1-Of+DE7dci2Xc7/HzHTg+D/KkCKA=",
      "requires": {
        "babel-runtime": "^6.26.0",
        "babel-types": "^6.26.0",
        "esutils": "^2.0.2"
      }
    },
    "babel-helper-call-delegate": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-helper-call-delegate/-/babel-helper-call-delegate-6.24.1.tgz",
      "integrity": "sha1-7Oaqzdx25Bw0YfiL/Fdb0Nqi340=",
      "requires": {
        "babel-helper-hoist-variables": "^6.24.1",
        "babel-runtime": "^6.22.0",
        "babel-traverse": "^6.24.1",
        "babel-types": "^6.24.1"
      }
    },
    "babel-helper-define-map": {
      "version": "6.26.0",
      "resolved": "https://registry.npmjs.org/babel-helper-define-map/-/babel-helper-define-map-6.26.0.tgz",
      "integrity": "sha1-pfVtq0GiX5fstJjH66ypgZ+Vvl8=",
      "requires": {
        "babel-helper-function-name": "^6.24.1",
        "babel-runtime": "^6.26.0",
        "babel-types": "^6.26.0",
        "lodash": "^4.17.4"
      }
    },
    "babel-helper-function-name": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-helper-function-name/-/babel-helper-function-name-6.24.1.tgz",
      "integrity": "sha1-00dbjAPtmCQqJbSDUasYOZ01gKk=",
      "requires": {
        "babel-helper-get-function-arity": "^6.24.1",
        "babel-runtime": "^6.22.0",
        "babel-template": "^6.24.1",
        "babel-traverse": "^6.24.1",
        "babel-types": "^6.24.1"
      }
    },
    "babel-helper-get-function-arity": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-helper-get-function-arity/-/babel-helper-get-function-arity-6.24.1.tgz",
      "integrity": "sha1-j3eCqpNAfEHTqlCQj4mwMbG2hT0=",
      "requires": {
        "babel-runtime": "^6.22.0",
        "babel-types": "^6.24.1"
      }
    },
    "babel-helper-hoist-variables": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-helper-hoist-variables/-/babel-helper-hoist-variables-6.24.1.tgz",
      "integrity": "sha1-HssnaJydJVE+rbyZFKc/VAi+enY=",
      "requires": {
        "babel-runtime": "^6.22.0",
        "babel-types": "^6.24.1"
      }
    },
    "babel-helper-optimise-call-expression": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-helper-optimise-call-expression/-/babel-helper-optimise-call-expression-6.24.1.tgz",
      "integrity": "sha1-96E0J7qfc/j0+pk8VKl4gtEkQlc=",
      "requires": {
        "babel-runtime": "^6.22.0",
        "babel-types": "^6.24.1"
      }
    },
    "babel-helper-replace-supers": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-helper-replace-supers/-/babel-helper-replace-supers-6.24.1.tgz",
      "integrity": "sha1-v22/5Dk40XNpohPKiov3S2qQqxo=",
      "requires": {
        "babel-helper-optimise-call-expression": "^6.24.1",
        "babel-messages": "^6.23.0",
        "babel-runtime": "^6.22.0",
        "babel-template": "^6.24.1",
        "babel-traverse": "^6.24.1",
        "babel-types": "^6.24.1"
      }
    },
    "babel-helpers": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-helpers/-/babel-helpers-6.24.1.tgz",
      "integrity": "sha1-NHHenK7DiOXIUOWX5Yom3fN2ArI=",
      "requires": {
        "babel-runtime": "^6.22.0",
        "babel-template": "^6.24.1"
      }
    },
    "babel-messages": {
      "version": "6.23.0",
      "resolved": "https://registry.npmjs.org/babel-messages/-/babel-messages-6.23.0.tgz",
      "integrity": "sha1-8830cDhYA1sqKVHG7F7fbGLyYw4=",
      "requires": {
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-check-es2015-constants": {
      "version": "6.22.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-check-es2015-constants/-/babel-plugin-check-es2015-constants-6.22.0.tgz",
      "integrity": "sha1-NRV7EBQm/S/9PaP3XH0ekYNbv4o=",
      "requires": {
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-module-resolver": {
      "version": "3.2.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-module-resolver/-/babel-plugin-module-resolver-3.2.0.tgz",
      "integrity": "sha512-tjR0GvSndzPew/Iayf4uICWZqjBwnlMWjSx6brryfQ81F9rxBVqwDJtFCV8oOs0+vJeefK9TmdZtkIFdFe1UnA==",
      "requires": {
        "find-babel-config": "^1.1.0",
        "glob": "^7.1.2",
        "pkg-up": "^2.0.0",
        "reselect": "^3.0.1",
        "resolve": "^1.4.0"
      }
    },
    "babel-plugin-syntax-class-properties": {
      "version": "6.13.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-syntax-class-properties/-/babel-plugin-syntax-class-properties-6.13.0.tgz",
      "integrity": "sha1-1+sjt5oxf4VDlixQW4J8fWysJ94="
    },
    "babel-plugin-syntax-flow": {
      "version": "6.18.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-syntax-flow/-/babel-plugin-syntax-flow-6.18.0.tgz",
      "integrity": "sha1-TDqyCiryaqIM0lmVw5jE63AxDI0="
    },
    "babel-plugin-syntax-jsx": {
      "version": "6.18.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-syntax-jsx/-/babel-plugin-syntax-jsx-6.18.0.tgz",
      "integrity": "sha1-CvMqmm4Tyno/1QaeYtew9Y0NiUY="
    },
    "babel-plugin-syntax-object-rest-spread": {
      "version": "6.13.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-syntax-object-rest-spread/-/babel-plugin-syntax-object-rest-spread-6.13.0.tgz",
      "integrity": "sha1-/WU28rzhODb/o6VFjEkDpZe7O/U="
    },
    "babel-plugin-syntax-trailing-function-commas": {
      "version": "6.22.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-syntax-trailing-function-commas/-/babel-plugin-syntax-trailing-function-commas-6.22.0.tgz",
      "integrity": "sha1-ugNgk3+NBuQBgKQ/4NVhb/9TLPM="
    },
    "babel-plugin-transform-class-properties": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-class-properties/-/babel-plugin-transform-class-properties-6.24.1.tgz",
      "integrity": "sha1-anl2PqYdM9NvN7YRqp3vgagbRqw=",
      "requires": {
        "babel-helper-function-name": "^6.24.1",
        "babel-plugin-syntax-class-properties": "^6.8.0",
        "babel-runtime": "^6.22.0",
        "babel-template": "^6.24.1"
      }
    },
    "babel-plugin-transform-es2015-arrow-functions": {
      "version": "6.22.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-arrow-functions/-/babel-plugin-transform-es2015-arrow-functions-6.22.0.tgz",
      "integrity": "sha1-RSaSy3EdX3ncf4XkQM5BufJE0iE=",
      "requires": {
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-transform-es2015-block-scoped-functions": {
      "version": "6.22.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-block-scoped-functions/-/babel-plugin-transform-es2015-block-scoped-functions-6.22.0.tgz",
      "integrity": "sha1-u8UbSflk1wy42OC5ToICRs46YUE=",
      "requires": {
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-transform-es2015-block-scoping": {
      "version": "6.26.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-block-scoping/-/babel-plugin-transform-es2015-block-scoping-6.26.0.tgz",
      "integrity": "sha1-1w9SmcEwjQXBL0Y4E7CgnnOxiV8=",
      "requires": {
        "babel-runtime": "^6.26.0",
        "babel-template": "^6.26.0",
        "babel-traverse": "^6.26.0",
        "babel-types": "^6.26.0",
        "lodash": "^4.17.4"
      }
    },
    "babel-plugin-transform-es2015-classes": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-classes/-/babel-plugin-transform-es2015-classes-6.24.1.tgz",
      "integrity": "sha1-WkxYpQyclGHlZLSyo7+ryXolhNs=",
      "requires": {
        "babel-helper-define-map": "^6.24.1",
        "babel-helper-function-name": "^6.24.1",
        "babel-helper-optimise-call-expression": "^6.24.1",
        "babel-helper-replace-supers": "^6.24.1",
        "babel-messages": "^6.23.0",
        "babel-runtime": "^6.22.0",
        "babel-template": "^6.24.1",
        "babel-traverse": "^6.24.1",
        "babel-types": "^6.24.1"
      }
    },
    "babel-plugin-transform-es2015-computed-properties": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-computed-properties/-/babel-plugin-transform-es2015-computed-properties-6.24.1.tgz",
      "integrity": "sha1-b+Ko0WiV1WNPTNmZttNICjCBWbM=",
      "requires": {
        "babel-runtime": "^6.22.0",
        "babel-template": "^6.24.1"
      }
    },
    "babel-plugin-transform-es2015-destructuring": {
      "version": "6.23.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-destructuring/-/babel-plugin-transform-es2015-destructuring-6.23.0.tgz",
      "integrity": "sha1-mXux8auWf2gtKwh2/jWNYOdlxW0=",
      "requires": {
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-transform-es2015-for-of": {
      "version": "6.23.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-for-of/-/babel-plugin-transform-es2015-for-of-6.23.0.tgz",
      "integrity": "sha1-9HyVsrYT3x0+zC/bdXNiPHUkhpE=",
      "requires": {
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-transform-es2015-function-name": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-function-name/-/babel-plugin-transform-es2015-function-name-6.24.1.tgz",
      "integrity": "sha1-g0yJhTvDaxrw86TF26qU/Y6sqos=",
      "requires": {
        "babel-helper-function-name": "^6.24.1",
        "babel-runtime": "^6.22.0",
        "babel-types": "^6.24.1"
      }
    },
    "babel-plugin-transform-es2015-literals": {
      "version": "6.22.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-literals/-/babel-plugin-transform-es2015-literals-6.22.0.tgz",
      "integrity": "sha1-T1SgLWzWbPkVKAAZox0xklN3yi4=",
      "requires": {
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-transform-es2015-modules-commonjs": {
      "version": "6.26.2",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-modules-commonjs/-/babel-plugin-transform-es2015-modules-commonjs-6.26.2.tgz",
      "integrity": "sha512-CV9ROOHEdrjcwhIaJNBGMBCodN+1cfkwtM1SbUHmvyy35KGT7fohbpOxkE2uLz1o6odKK2Ck/tz47z+VqQfi9Q==",
      "requires": {
        "babel-plugin-transform-strict-mode": "^6.24.1",
        "babel-runtime": "^6.26.0",
        "babel-template": "^6.26.0",
        "babel-types": "^6.26.0"
      }
    },
    "babel-plugin-transform-es2015-object-super": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-object-super/-/babel-plugin-transform-es2015-object-super-6.24.1.tgz",
      "integrity": "sha1-JM72muIcuDp/hgPa0CH1cusnj40=",
      "requires": {
        "babel-helper-replace-supers": "^6.24.1",
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-transform-es2015-parameters": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-parameters/-/babel-plugin-transform-es2015-parameters-6.24.1.tgz",
      "integrity": "sha1-V6w1GrScrxSpfNE7CfZv3wpiXys=",
      "requires": {
        "babel-helper-call-delegate": "^6.24.1",
        "babel-helper-get-function-arity": "^6.24.1",
        "babel-runtime": "^6.22.0",
        "babel-template": "^6.24.1",
        "babel-traverse": "^6.24.1",
        "babel-types": "^6.24.1"
      }
    },
    "babel-plugin-transform-es2015-shorthand-properties": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-shorthand-properties/-/babel-plugin-transform-es2015-shorthand-properties-6.24.1.tgz",
      "integrity": "sha1-JPh11nIch2YbvZmkYi5R8U3jiqA=",
      "requires": {
        "babel-runtime": "^6.22.0",
        "babel-types": "^6.24.1"
      }
    },
    "babel-plugin-transform-es2015-spread": {
      "version": "6.22.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-spread/-/babel-plugin-transform-es2015-spread-6.22.0.tgz",
      "integrity": "sha1-1taKmfia7cRTbIGlQujdnxdG+NE=",
      "requires": {
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-transform-es2015-template-literals": {
      "version": "6.22.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es2015-template-literals/-/babel-plugin-transform-es2015-template-literals-6.22.0.tgz",
      "integrity": "sha1-qEs0UPfp+PH2g51taH2oS7EjbY0=",
      "requires": {
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-transform-es3-member-expression-literals": {
      "version": "6.22.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es3-member-expression-literals/-/babel-plugin-transform-es3-member-expression-literals-6.22.0.tgz",
      "integrity": "sha1-cz00RPPsxBvvjtGmpOCWV7iWnrs=",
      "requires": {
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-transform-es3-property-literals": {
      "version": "6.22.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-es3-property-literals/-/babel-plugin-transform-es3-property-literals-6.22.0.tgz",
      "integrity": "sha1-sgeNWELiKr9A9z6M3pzTcRq9V1g=",
      "requires": {
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-transform-flow-strip-types": {
      "version": "6.22.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-flow-strip-types/-/babel-plugin-transform-flow-strip-types-6.22.0.tgz",
      "integrity": "sha1-hMtnKTXUNxT9wyvOhFaNh0Qc988=",
      "requires": {
        "babel-plugin-syntax-flow": "^6.18.0",
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-transform-object-rest-spread": {
      "version": "6.26.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-object-rest-spread/-/babel-plugin-transform-object-rest-spread-6.26.0.tgz",
      "integrity": "sha1-DzZpLVD+9rfi1LOsFHgTepY7ewY=",
      "requires": {
        "babel-plugin-syntax-object-rest-spread": "^6.8.0",
        "babel-runtime": "^6.26.0"
      }
    },
    "babel-plugin-transform-react-display-name": {
      "version": "6.25.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-react-display-name/-/babel-plugin-transform-react-display-name-6.25.0.tgz",
      "integrity": "sha1-Z+K/Hx6ck6sI25Z5LgU5K/LMKNE=",
      "requires": {
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-transform-react-jsx": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-react-jsx/-/babel-plugin-transform-react-jsx-6.24.1.tgz",
      "integrity": "sha1-hAoCjn30YN/DotKfDA2R9jduZqM=",
      "requires": {
        "babel-helper-builder-react-jsx": "^6.24.1",
        "babel-plugin-syntax-jsx": "^6.8.0",
        "babel-runtime": "^6.22.0"
      }
    },
    "babel-plugin-transform-strict-mode": {
      "version": "6.24.1",
      "resolved": "https://registry.npmjs.org/babel-plugin-transform-strict-mode/-/babel-plugin-transform-strict-mode-6.24.1.tgz",
      "integrity": "sha1-1fr3qleKZbvlkc9e2uBKDGcCB1g=",
      "requires": {
        "babel-runtime": "^6.22.0",
        "babel-types": "^6.24.1"
      }
    },
    "babel-preset-expo": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/babel-preset-expo/-/babel-preset-expo-5.0.0.tgz",
      "integrity": "sha512-pDtkAIafvQLAZ5dQ/6I9okkiZLw9IBR8ItRzAyUO4j2rUMB9ey6yZTTE77AKWq5HhxhY53Hic8Zl0vSDMTXI0A==",
      "requires": {
        "@babel/plugin-proposal-decorators": "^7.1.0",
        "babel-plugin-module-resolver": "^3.1.1",
        "metro-react-native-babel-preset": "^0.49.0"
      }
    },
    "babel-preset-fbjs": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/babel-preset-fbjs/-/babel-preset-fbjs-2.3.0.tgz",
      "integrity": "sha512-ZOpAI1/bN0Y3J1ZAK9gRsFkHy9gGgJoDRUjtUCla/129LC7uViq9nIK22YdHfey8szohYoZY3f9L2lGOv0Edqw==",
      "requires": {
        "babel-plugin-check-es2015-constants": "^6.8.0",
        "babel-plugin-syntax-class-properties": "^6.8.0",
        "babel-plugin-syntax-flow": "^6.8.0",
        "babel-plugin-syntax-jsx": "^6.8.0",
        "babel-plugin-syntax-object-rest-spread": "^6.8.0",
        "babel-plugin-syntax-trailing-function-commas": "^6.8.0",
        "babel-plugin-transform-class-properties": "^6.8.0",
        "babel-plugin-transform-es2015-arrow-functions": "^6.8.0",
        "babel-plugin-transform-es2015-block-scoped-functions": "^6.8.0",
        "babel-plugin-transform-es2015-block-scoping": "^6.8.0",
        "babel-plugin-transform-es2015-classes": "^6.8.0",
        "babel-plugin-transform-es2015-computed-properties": "^6.8.0",
        "babel-plugin-transform-es2015-destructuring": "^6.8.0",
        "babel-plugin-transform-es2015-for-of": "^6.8.0",
        "babel-plugin-transform-es2015-function-name": "^6.8.0",
        "babel-plugin-transform-es2015-literals": "^6.8.0",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.8.0",
        "babel-plugin-transform-es2015-object-super": "^6.8.0",
        "babel-plugin-transform-es2015-parameters": "^6.8.0",
        "babel-plugin-transform-es2015-shorthand-properties": "^6.8.0",
        "babel-plugin-transform-es2015-spread": "^6.8.0",
        "babel-plugin-transform-es2015-template-literals": "^6.8.0",
        "babel-plugin-transform-es3-member-expression-literals": "^6.8.0",
        "babel-plugin-transform-es3-property-literals": "^6.8.0",
        "babel-plugin-transform-flow-strip-types": "^6.8.0",
        "babel-plugin-transform-object-rest-spread": "^6.8.0",
        "babel-plugin-transform-react-display-name": "^6.8.0",
        "babel-plugin-transform-react-jsx": "^6.8.0"
      }
    },
    "babel-register": {
      "version": "6.26.0",
      "resolved": "https://registry.npmjs.org/babel-register/-/babel-register-6.26.0.tgz",
      "integrity": "sha1-btAhFz4vy0htestFxgCahW9kcHE=",
      "requires": {
        "babel-core": "^6.26.0",
        "babel-runtime": "^6.26.0",
        "core-js": "^2.5.0",
        "home-or-tmp": "^2.0.0",
        "lodash": "^4.17.4",
        "mkdirp": "^0.5.1",
        "source-map-support": "^0.4.15"
      }
    },
    "babel-runtime": {
      "version": "6.26.0",
      "resolved": "https://registry.npmjs.org/babel-runtime/-/babel-runtime-6.26.0.tgz",
      "integrity": "sha1-llxwWGaOgrVde/4E/yM3vItWR/4=",
      "requires": {
        "core-js": "^2.4.0",
        "regenerator-runtime": "^0.11.0"
      }
    },
    "babel-template": {
      "version": "6.26.0",
      "resolved": "https://registry.npmjs.org/babel-template/-/babel-template-6.26.0.tgz",
      "integrity": "sha1-3gPi0WOWsGn0bdn/+FIfsaDjXgI=",
      "requires": {
        "babel-runtime": "^6.26.0",
        "babel-traverse": "^6.26.0",
        "babel-types": "^6.26.0",
        "babylon": "^6.18.0",
        "lodash": "^4.17.4"
      }
    },
    "babel-traverse": {
      "version": "6.26.0",
      "resolved": "https://registry.npmjs.org/babel-traverse/-/babel-traverse-6.26.0.tgz",
      "integrity": "sha1-RqnL1+3MYsjlwGTi0tjQ9ANXZu4=",
      "requires": {
        "babel-code-frame": "^6.26.0",
        "babel-messages": "^6.23.0",
        "babel-runtime": "^6.26.0",
        "babel-types": "^6.26.0",
        "babylon": "^6.18.0",
        "debug": "^2.6.8",
        "globals": "^9.18.0",
        "invariant": "^2.2.2",
        "lodash": "^4.17.4"
      },
      "dependencies": {
        "globals": {
          "version": "9.18.0",
          "resolved": "https://registry.npmjs.org/globals/-/globals-9.18.0.tgz",
          "integrity": "sha512-S0nG3CLEQiY/ILxqtztTWH/3iRRdyBLw6KMDxnKMchrtbj2OFmehVh0WUCfW3DUrIgx/qFrJPICrq4Z4sTR9UQ=="
        }
      }
    },
    "babel-types": {
      "version": "6.26.0",
      "resolved": "https://registry.npmjs.org/babel-types/-/babel-types-6.26.0.tgz",
      "integrity": "sha1-o7Bz+Uq0nrb6Vc1lInozQ4BjJJc=",
      "requires": {
        "babel-runtime": "^6.26.0",
        "esutils": "^2.0.2",
        "lodash": "^4.17.4",
        "to-fast-properties": "^1.0.3"
      },
      "dependencies": {
        "to-fast-properties": {
          "version": "1.0.3",
          "resolved": "https://registry.npmjs.org/to-fast-properties/-/to-fast-properties-1.0.3.tgz",
          "integrity": "sha1-uDVx+k2MJbguIxsG46MFXeTKGkc="
        }
      }
    },
    "babylon": {
      "version": "6.18.0",
      "resolved": "https://registry.npmjs.org/babylon/-/babylon-6.18.0.tgz",
      "integrity": "sha512-q/UEjfGJ2Cm3oKV71DJz9d25TPnq5rhBVL2Q4fA5wcC3jcrdn7+SssEybFIxwAvvP+YCsCYNKughoF33GxgycQ=="
    },
    "balanced-match": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/balanced-match/-/balanced-match-1.0.0.tgz",
      "integrity": "sha1-ibTRmasr7kneFk6gK4nORi1xt2c="
    },
    "base": {
      "version": "0.11.2",
      "resolved": "https://registry.npmjs.org/base/-/base-0.11.2.tgz",
      "integrity": "sha512-5T6P4xPgpp0YDFvSWwEZ4NoE3aM4QBQXDzmVbraCkFj8zHM+mba8SyqB5DbZWyR7mYHo6Y7BdQo3MoA4m0TeQg==",
      "requires": {
        "cache-base": "^1.0.1",
        "class-utils": "^0.3.5",
        "component-emitter": "^1.2.1",
        "define-property": "^1.0.0",
        "isobject": "^3.0.1",
        "mixin-deep": "^1.2.0",
        "pascalcase": "^0.1.1"
      },
      "dependencies": {
        "define-property": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-1.0.0.tgz",
          "integrity": "sha1-dp66rz9KY6rTr56NMEybvnm/sOY=",
          "requires": {
            "is-descriptor": "^1.0.0"
          }
        },
        "is-accessor-descriptor": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-1.0.0.tgz",
          "integrity": "sha512-m5hnHTkcVsPfqx3AKlyttIPb7J+XykHvJP2B9bZDjlhLIoEq4XoK64Vg7boZlVWYK6LUY94dYPEE7Lh0ZkZKcQ==",
          "requires": {
            "kind-of": "^6.0.0"
          }
        },
        "is-data-descriptor": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-1.0.0.tgz",
          "integrity": "sha512-jbRXy1FmtAoCjQkVmIVYwuuqDFUbaOeDjmed1tOGPrsMhtJA4rD9tkgA0F1qJ3gRFRXcHYVkdeaP50Q5rE/jLQ==",
          "requires": {
            "kind-of": "^6.0.0"
          }
        },
        "is-descriptor": {
          "version": "1.0.2",
          "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-1.0.2.tgz",
          "integrity": "sha512-2eis5WqQGV7peooDyLmNEPUrps9+SXX5c9pL3xEB+4e9HnGuDa7mB7kHxHw4CbqS9k1T2hOH3miL8n8WtiYVtg==",
          "requires": {
            "is-accessor-descriptor": "^1.0.0",
            "is-data-descriptor": "^1.0.0",
            "kind-of": "^6.0.2"
          }
        },
        "isobject": {
          "version": "3.0.1",
          "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
          "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8="
        },
        "kind-of": {
          "version": "6.0.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-6.0.2.tgz",
          "integrity": "sha512-s5kLOcnH0XqDO+FvuaLX8DDjZ18CGFk7VygH40QoKPUQhW4e2rvM0rwUq0t8IQDOwYSeLK01U90OjzBTme2QqA=="
        }
      }
    },
    "base64-js": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/base64-js/-/base64-js-1.3.0.tgz",
      "integrity": "sha512-ccav/yGvoa80BQDljCxsmmQ3Xvx60/UpBIij5QN21W3wBi/hhIC9OoO+KLpu9IJTS9j4DRVJ3aDDF9cMSoa2lw=="
    },
    "basic-auth": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/basic-auth/-/basic-auth-2.0.1.tgz",
      "integrity": "sha512-NF+epuEdnUYVlGuhaxbbq+dvJttwLnGY+YixlXlME5KpQ5W3CnXA5cVTneY3SPbPDRkcjMbifrwmFYcClgOZeg==",
      "requires": {
        "safe-buffer": "5.1.2"
      }
    },
    "big-integer": {
      "version": "1.6.41",
      "resolved": "https://registry.npmjs.org/big-integer/-/big-integer-1.6.41.tgz",
      "integrity": "sha512-d5AT9lMTYJ/ZE/4gzxb+5ttPcRWljVsvv7lF1w9KzkPhVUhBtHrjDo1J8swfZKepfLsliDhYa31zRYwcD0Yg9w=="
    },
    "big.js": {
      "version": "5.2.2",
      "resolved": "https://registry.npmjs.org/big.js/-/big.js-5.2.2.tgz",
      "integrity": "sha512-vyL2OymJxmarO8gxMr0mhChsO9QGwhynfuu4+MHTAW6czfq9humCB7rKpUjDd9YUiDPU4mzpyupFSvOClAwbmQ=="
    },
    "blueimp-md5": {
      "version": "2.10.0",
      "resolved": "https://registry.npmjs.org/blueimp-md5/-/blueimp-md5-2.10.0.tgz",
      "integrity": "sha512-EkNUOi7tpV68TqjpiUz9D9NcT8um2+qtgntmMbi5UKssVX2m/2PLqotcric0RE63pB3HPN/fjf3cKHN2ufGSUQ=="
    },
    "bplist-creator": {
      "version": "0.0.7",
      "resolved": "https://registry.npmjs.org/bplist-creator/-/bplist-creator-0.0.7.tgz",
      "integrity": "sha1-N98VNgkoJLh8QvlXsBNEEXNyrkU=",
      "requires": {
        "stream-buffers": "~2.2.0"
      }
    },
    "bplist-parser": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/bplist-parser/-/bplist-parser-0.1.1.tgz",
      "integrity": "sha1-1g1dzCDLptx+HymbNdPh+V2vuuY=",
      "requires": {
        "big-integer": "^1.6.7"
      }
    },
    "brace-expansion": {
      "version": "1.1.11",
      "resolved": "https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.11.tgz",
      "integrity": "sha512-iCuPHDFgrHX7H2vEI/5xpz07zSHB00TpugqhmYtVmMO6518mCuRMoOYFldEBl0g187ufozdaHgWKcYFb61qGiA==",
      "requires": {
        "balanced-match": "^1.0.0",
        "concat-map": "0.0.1"
      }
    },
    "braces": {
      "version": "1.8.5",
      "resolved": "https://registry.npmjs.org/braces/-/braces-1.8.5.tgz",
      "integrity": "sha1-uneWLhLf+WnWt2cR6RS3N4V79qc=",
      "requires": {
        "expand-range": "^1.8.1",
        "preserve": "^0.2.0",
        "repeat-element": "^1.1.2"
      }
    },
    "bser": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/bser/-/bser-2.0.0.tgz",
      "integrity": "sha1-mseNPtXZFYBP2HrLFYvHlxR6Fxk=",
      "requires": {
        "node-int64": "^0.4.0"
      }
    },
    "buffer-alloc": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/buffer-alloc/-/buffer-alloc-1.2.0.tgz",
      "integrity": "sha512-CFsHQgjtW1UChdXgbyJGtnm+O/uLQeZdtbDo8mfUgYXCHSM1wgrVxXm6bSyrUuErEb+4sYVGCzASBRot7zyrow==",
      "requires": {
        "buffer-alloc-unsafe": "^1.1.0",
        "buffer-fill": "^1.0.0"
      }
    },
    "buffer-alloc-unsafe": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/buffer-alloc-unsafe/-/buffer-alloc-unsafe-1.1.0.tgz",
      "integrity": "sha512-TEM2iMIEQdJ2yjPJoSIsldnleVaAk1oW3DBVUykyOLsEsFmEc9kn+SFFPz+gl54KQNxlDnAwCXosOS9Okx2xAg=="
    },
    "buffer-fill": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/buffer-fill/-/buffer-fill-1.0.0.tgz",
      "integrity": "sha1-+PeLdniYiO858gXNY39o5wISKyw="
    },
    "buffer-from": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/buffer-from/-/buffer-from-1.1.1.tgz",
      "integrity": "sha512-MQcXEUbCKtEo7bhqEs6560Hyd4XaovZlO/k9V3hjVUF/zwW7KBVdSK4gIt/bzwS9MbR5qob+F5jusZsb0YQK2A=="
    },
    "bytes": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/bytes/-/bytes-3.0.0.tgz",
      "integrity": "sha1-0ygVQE1olpn4Wk6k+odV3ROpYEg="
    },
    "cache-base": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/cache-base/-/cache-base-1.0.1.tgz",
      "integrity": "sha512-AKcdTnFSWATd5/GCPRxr2ChwIJ85CeyrEyjRHlKxQ56d4XJMGym0uAiKn0xbLOGOl3+yRpOTi484dVCEc5AUzQ==",
      "requires": {
        "collection-visit": "^1.0.0",
        "component-emitter": "^1.2.1",
        "get-value": "^2.0.6",
        "has-value": "^1.0.0",
        "isobject": "^3.0.1",
        "set-value": "^2.0.0",
        "to-object-path": "^0.3.0",
        "union-value": "^1.0.0",
        "unset-value": "^1.0.0"
      },
      "dependencies": {
        "isobject": {
          "version": "3.0.1",
          "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
          "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8="
        }
      }
    },
    "caller-callsite": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/caller-callsite/-/caller-callsite-2.0.0.tgz",
      "integrity": "sha1-hH4PzgoiN1CpoCfFSzNzGtMVQTQ=",
      "requires": {
        "callsites": "^2.0.0"
      }
    },
    "caller-path": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/caller-path/-/caller-path-2.0.0.tgz",
      "integrity": "sha1-Ro+DBE42mrIBD6xfBs7uFbsssfQ=",
      "requires": {
        "caller-callsite": "^2.0.0"
      }
    },
    "callsites": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/callsites/-/callsites-2.0.0.tgz",
      "integrity": "sha1-BuuE8A7qQT2oav/vrL/7Ngk7PFA="
    },
    "camelcase": {
      "version": "4.1.0",
      "resolved": "https://registry.npmjs.org/camelcase/-/camelcase-4.1.0.tgz",
      "integrity": "sha1-1UVjW+HjPFQmScaRc+Xeas+uNN0="
    },
    "capture-exit": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/capture-exit/-/capture-exit-1.2.0.tgz",
      "integrity": "sha1-HF/MSJ/QqwDU8ax64QcuMXP7q28=",
      "requires": {
        "rsvp": "^3.3.3"
      }
    },
    "chalk": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz",
      "integrity": "sha1-qBFcVeSnAv5NFQq9OHKCKn4J/Jg=",
      "requires": {
        "ansi-styles": "^2.2.1",
        "escape-string-regexp": "^1.0.2",
        "has-ansi": "^2.0.0",
        "strip-ansi": "^3.0.0",
        "supports-color": "^2.0.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "2.2.1",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz",
          "integrity": "sha1-tDLdM1i2NM914eRmQ2gkBTPB3b4="
        }
      }
    },
    "chardet": {
      "version": "0.4.2",
      "resolved": "https://registry.npmjs.org/chardet/-/chardet-0.4.2.tgz",
      "integrity": "sha1-tUc7M9yXxCTl2Y3IfVXU2KKci/I="
    },
    "clamp": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/clamp/-/clamp-1.0.1.tgz",
      "integrity": "sha1-ZqDmQBGBbjcZaCj9yMjBRzEshjQ="
    },
    "class-utils": {
      "version": "0.3.6",
      "resolved": "https://registry.npmjs.org/class-utils/-/class-utils-0.3.6.tgz",
      "integrity": "sha512-qOhPa/Fj7s6TY8H8esGu5QNpMMQxz79h+urzrNYN6mn+9BnxlDGf5QZ+XeCDsxSjPqsSR56XOZOJmpeurnLMeg==",
      "requires": {
        "arr-union": "^3.1.0",
        "define-property": "^0.2.5",
        "isobject": "^3.0.0",
        "static-extend": "^0.1.1"
      },
      "dependencies": {
        "arr-union": {
          "version": "3.1.0",
          "resolved": "https://registry.npmjs.org/arr-union/-/arr-union-3.1.0.tgz",
          "integrity": "sha1-45sJrqne+Gao8gbiiK9jkZuuOcQ="
        },
        "define-property": {
          "version": "0.2.5",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
          "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
          "requires": {
            "is-descriptor": "^0.1.0"
          }
        },
        "isobject": {
          "version": "3.0.1",
          "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
          "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8="
        }
      }
    },
    "classnames": {
      "version": "2.2.6",
      "resolved": "https://registry.npmjs.org/classnames/-/classnames-2.2.6.tgz",
      "integrity": "sha512-JR/iSQOSt+LQIWwrwEzJ9uk0xfN3mTVYMwt1Ir5mUcSN6pU+V4zQFFaJsclJbPuAUQH+yfWef6tm7l1quW3C8Q=="
    },
    "cli-cursor": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/cli-cursor/-/cli-cursor-2.1.0.tgz",
      "integrity": "sha1-s12sN2R5+sw+lHR9QdDQ9SOP/LU=",
      "requires": {
        "restore-cursor": "^2.0.0"
      }
    },
    "cli-width": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/cli-width/-/cli-width-2.2.0.tgz",
      "integrity": "sha1-/xnt6Kml5XkyQUewwR8PvLq+1jk="
    },
    "cliui": {
      "version": "3.2.0",
      "resolved": "https://registry.npmjs.org/cliui/-/cliui-3.2.0.tgz",
      "integrity": "sha1-EgYBU3qRbSmUD5NNo7SNWFo5IT0=",
      "requires": {
        "string-width": "^1.0.1",
        "strip-ansi": "^3.0.1",
        "wrap-ansi": "^2.0.0"
      },
      "dependencies": {
        "string-width": {
          "version": "1.0.2",
          "resolved": "https://registry.npmjs.org/string-width/-/string-width-1.0.2.tgz",
          "integrity": "sha1-EYvfW4zcUaKn5w0hHgfisLmxB9M=",
          "requires": {
            "code-point-at": "^1.0.0",
            "is-fullwidth-code-point": "^1.0.0",
            "strip-ansi": "^3.0.0"
          }
        }
      }
    },
    "code-point-at": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/code-point-at/-/code-point-at-1.1.0.tgz",
      "integrity": "sha1-DQcLTQQ6W+ozovGkDi7bPZpMz3c="
    },
    "collection-visit": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/collection-visit/-/collection-visit-1.0.0.tgz",
      "integrity": "sha1-S8A3PBZLwykbTTaMgpzxqApZ3KA=",
      "requires": {
        "map-visit": "^1.0.0",
        "object-visit": "^1.0.0"
      }
    },
    "color": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color/-/color-2.0.1.tgz",
      "integrity": "sha512-ubUCVVKfT7r2w2D3qtHakj8mbmKms+tThR8gI8zEYCbUBl8/voqFGt3kgBqGwXAopgXybnkuOq+qMYCRrp4cXw==",
      "requires": {
        "color-convert": "^1.9.1",
        "color-string": "^1.5.2"
      }
    },
    "color-convert": {
      "version": "1.9.3",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-1.9.3.tgz",
      "integrity": "sha512-QfAUtd+vFdAtFQcC8CCyYt1fYWxSqAiK2cSD6zDB8N3cpsEBAvRxp9zOGg6G/SHHJYAT88/az/IuDGALsNVbGg==",
      "requires": {
        "color-name": "1.1.3"
      }
    },
    "color-name": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.3.tgz",
      "integrity": "sha1-p9BVi9icQveV3UIyj3QIMcpTvCU="
    },
    "color-string": {
      "version": "1.5.3",
      "resolved": "https://registry.npmjs.org/color-string/-/color-string-1.5.3.tgz",
      "integrity": "sha512-dC2C5qeWoYkxki5UAXapdjqO672AM4vZuPGRQfO8b5HKuKGBbKWpITyDYN7TOFKvRW7kOgAn3746clDBMDJyQw==",
      "requires": {
        "color-name": "^1.0.0",
        "simple-swizzle": "^0.2.2"
      }
    },
    "color-support": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/color-support/-/color-support-1.1.3.tgz",
      "integrity": "sha512-qiBjkpbMLO/HL68y+lh4q0/O1MZFj2RX6X/KmMa3+gJD3z+WwI1ZzDHysvqHGS3mP6mznPckpXmw1nI9cJjyRg=="
    },
    "commander": {
      "version": "2.19.0",
      "resolved": "https://registry.npmjs.org/commander/-/commander-2.19.0.tgz",
      "integrity": "sha512-6tvAOO+D6OENvRAh524Dh9jcfKTYDQAqvqezbCW82xj5X0pSrcpxtvRKHLG0yBY6SD7PSDrJaj+0AiOcKVd1Xg=="
    },
    "commondir": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/commondir/-/commondir-1.0.1.tgz",
      "integrity": "sha1-3dgA2gxmEnOTzKWVDqloo6rxJTs="
    },
    "component-emitter": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/component-emitter/-/component-emitter-1.2.1.tgz",
      "integrity": "sha1-E3kY1teCg/ffemt8WmPhQOaUJeY="
    },
    "compressible": {
      "version": "2.0.15",
      "resolved": "https://registry.npmjs.org/compressible/-/compressible-2.0.15.tgz",
      "integrity": "sha512-4aE67DL33dSW9gw4CI2H/yTxqHLNcxp0yS6jB+4h+wr3e43+1z7vm0HU9qXOH8j+qjKuL8+UtkOxYQSMq60Ylw==",
      "requires": {
        "mime-db": ">= 1.36.0 < 2"
      }
    },
    "compression": {
      "version": "1.7.3",
      "resolved": "https://registry.npmjs.org/compression/-/compression-1.7.3.tgz",
      "integrity": "sha512-HSjyBG5N1Nnz7tF2+O7A9XUhyjru71/fwgNb7oIsEVHR0WShfs2tIS/EySLgiTe98aOK18YDlMXpzjCXY/n9mg==",
      "requires": {
        "accepts": "~1.3.5",
        "bytes": "3.0.0",
        "compressible": "~2.0.14",
        "debug": "2.6.9",
        "on-headers": "~1.0.1",
        "safe-buffer": "5.1.2",
        "vary": "~1.1.2"
      }
    },
    "concat-map": {
      "version": "0.0.1",
      "resolved": "https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz",
      "integrity": "sha1-2Klr13/Wjfd5OnMDajug1UBdR3s="
    },
    "concat-stream": {
      "version": "1.6.2",
      "resolved": "https://registry.npmjs.org/concat-stream/-/concat-stream-1.6.2.tgz",
      "integrity": "sha512-27HBghJxjiZtIk3Ycvn/4kbJk/1uZuJFfuPEns6LaEvpvG1f0hTea8lilrouyo9mVc2GWdcEZ8OLoGmSADlrCw==",
      "requires": {
        "buffer-from": "^1.0.0",
        "inherits": "^2.0.3",
        "readable-stream": "^2.2.2",
        "typedarray": "^0.0.6"
      }
    },
    "connect": {
      "version": "3.6.6",
      "resolved": "https://registry.npmjs.org/connect/-/connect-3.6.6.tgz",
      "integrity": "sha1-Ce/2xVr3I24TcTWnJXSFi2eG9SQ=",
      "requires": {
        "debug": "2.6.9",
        "finalhandler": "1.1.0",
        "parseurl": "~1.3.2",
        "utils-merge": "1.0.1"
      }
    },
    "convert-source-map": {
      "version": "1.6.0",
      "resolved": "https://registry.npmjs.org/convert-source-map/-/convert-source-map-1.6.0.tgz",
      "integrity": "sha512-eFu7XigvxdZ1ETfbgPBohgyQ/Z++C0eEhTor0qRwBw9unw+L0/6V8wkSuGgzdThkiS5lSpdptOQPD8Ak40a+7A==",
      "requires": {
        "safe-buffer": "~5.1.1"
      }
    },
    "copy-descriptor": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/copy-descriptor/-/copy-descriptor-0.1.1.tgz",
      "integrity": "sha1-Z29us8OZl8LuGsOpJP1hJHSPV40="
    },
    "core-js": {
      "version": "2.6.5",
      "resolved": "https://registry.npmjs.org/core-js/-/core-js-2.6.5.tgz",
      "integrity": "sha512-klh/kDpwX8hryYL14M9w/xei6vrv6sE8gTHDG7/T/+SEovB/G4ejwcfE/CBzO6Edsu+OETZMZ3wcX/EjUkrl5A=="
    },
    "core-util-is": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/core-util-is/-/core-util-is-1.0.2.tgz",
      "integrity": "sha1-tf1UIgqivFq1eqtxQMlAdUUDwac="
    },
    "cosmiconfig": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/cosmiconfig/-/cosmiconfig-5.1.0.tgz",
      "integrity": "sha512-kCNPvthka8gvLtzAxQXvWo4FxqRB+ftRZyPZNuab5ngvM9Y7yw7hbEysglptLgpkGX9nAOKTBVkHUAe8xtYR6Q==",
      "requires": {
        "import-fresh": "^2.0.0",
        "is-directory": "^0.3.1",
        "js-yaml": "^3.9.0",
        "lodash.get": "^4.4.2",
        "parse-json": "^4.0.0"
      },
      "dependencies": {
        "parse-json": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/parse-json/-/parse-json-4.0.0.tgz",
          "integrity": "sha1-vjX1Qlvh9/bHRxhPmKeIy5lHfuA=",
          "requires": {
            "error-ex": "^1.3.1",
            "json-parse-better-errors": "^1.0.1"
          }
        }
      }
    },
    "create-react-class": {
      "version": "15.6.3",
      "resolved": "https://registry.npmjs.org/create-react-class/-/create-react-class-15.6.3.tgz",
      "integrity": "sha512-M+/3Q6E6DLO6Yx3OwrWjwHBnvfXXYA7W+dFjt/ZDBemHO1DDZhsalX/NUtnTYclN6GfnBDRh4qRHjcDHmlJBJg==",
      "requires": {
        "fbjs": "^0.8.9",
        "loose-envify": "^1.3.1",
        "object-assign": "^4.1.1"
      }
    },
    "create-react-context": {
      "version": "0.2.2",
      "resolved": "https://registry.npmjs.org/create-react-context/-/create-react-context-0.2.2.tgz",
      "integrity": "sha512-KkpaLARMhsTsgp0d2NA/R94F/eDLbhXERdIq3LvX2biCAXcDvHYoOqHfWCHf1+OLj+HKBotLG3KqaOOf+C1C+A==",
      "requires": {
        "fbjs": "^0.8.0",
        "gud": "^1.0.0"
      }
    },
    "cross-spawn": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/cross-spawn/-/cross-spawn-5.1.0.tgz",
      "integrity": "sha1-6L0O/uWPz/b4+UUQoKVUu/ojVEk=",
      "requires": {
        "lru-cache": "^4.0.1",
        "shebang-command": "^1.2.0",
        "which": "^1.2.9"
      }
    },
    "debug": {
      "version": "2.6.9",
      "resolved": "https://registry.npmjs.org/debug/-/debug-2.6.9.tgz",
      "integrity": "sha512-bC7ElrdJaJnPbAP+1EotYvqZsb3ecl5wi6Bfi6BJTUcNowp6cvspg0jXznRTKDjm/E7AdgFBVeAPVMNcKGsHMA==",
      "requires": {
        "ms": "2.0.0"
      }
    },
    "decamelize": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/decamelize/-/decamelize-1.2.0.tgz",
      "integrity": "sha1-9lNNFRSCabIDUue+4m9QH5oZEpA="
    },
    "decode-uri-component": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/decode-uri-component/-/decode-uri-component-0.2.0.tgz",
      "integrity": "sha1-6zkTMzRYd1y4TNGh+uBiEGu4dUU="
    },
    "dedent": {
      "version": "0.6.0",
      "resolved": "https://registry.npmjs.org/dedent/-/dedent-0.6.0.tgz",
      "integrity": "sha1-Dm2o8M5Sg471zsXI+TlrDBtko8s="
    },
    "deepmerge": {
      "version": "2.2.1",
      "resolved": "https://registry.npmjs.org/deepmerge/-/deepmerge-2.2.1.tgz",
      "integrity": "sha512-R9hc1Xa/NOBi9WRVUWg19rl1UB7Tt4kuPd+thNJgFZoxXsTz7ncaPaeIm+40oSGuP33DfMb4sZt1QIGiJzC4EA=="
    },
    "define-property": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/define-property/-/define-property-2.0.2.tgz",
      "integrity": "sha512-jwK2UV4cnPpbcG7+VRARKTZPUWowwXA8bzH5NP6ud0oeAxyYPuGZUAC7hMugpCdz4BeSZl2Dl9k66CHJ/46ZYQ==",
      "requires": {
        "is-descriptor": "^1.0.2",
        "isobject": "^3.0.1"
      },
      "dependencies": {
        "is-accessor-descriptor": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-1.0.0.tgz",
          "integrity": "sha512-m5hnHTkcVsPfqx3AKlyttIPb7J+XykHvJP2B9bZDjlhLIoEq4XoK64Vg7boZlVWYK6LUY94dYPEE7Lh0ZkZKcQ==",
          "requires": {
            "kind-of": "^6.0.0"
          }
        },
        "is-data-descriptor": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-1.0.0.tgz",
          "integrity": "sha512-jbRXy1FmtAoCjQkVmIVYwuuqDFUbaOeDjmed1tOGPrsMhtJA4rD9tkgA0F1qJ3gRFRXcHYVkdeaP50Q5rE/jLQ==",
          "requires": {
            "kind-of": "^6.0.0"
          }
        },
        "is-descriptor": {
          "version": "1.0.2",
          "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-1.0.2.tgz",
          "integrity": "sha512-2eis5WqQGV7peooDyLmNEPUrps9+SXX5c9pL3xEB+4e9HnGuDa7mB7kHxHw4CbqS9k1T2hOH3miL8n8WtiYVtg==",
          "requires": {
            "is-accessor-descriptor": "^1.0.0",
            "is-data-descriptor": "^1.0.0",
            "kind-of": "^6.0.2"
          }
        },
        "isobject": {
          "version": "3.0.1",
          "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
          "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8="
        },
        "kind-of": {
          "version": "6.0.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-6.0.2.tgz",
          "integrity": "sha512-s5kLOcnH0XqDO+FvuaLX8DDjZ18CGFk7VygH40QoKPUQhW4e2rvM0rwUq0t8IQDOwYSeLK01U90OjzBTme2QqA=="
        }
      }
    },
    "delegates": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/delegates/-/delegates-1.0.0.tgz",
      "integrity": "sha1-hMbhWbgZBP3KWaDvRM2HDTElD5o="
    },
    "denodeify": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/denodeify/-/denodeify-1.2.1.tgz",
      "integrity": "sha1-OjYof1A05pnnV3kBBSwubJQlFjE="
    },
    "depd": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/depd/-/depd-1.1.2.tgz",
      "integrity": "sha1-m81S4UwJd2PnSbJ0xDRu0uVgtak="
    },
    "destroy": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/destroy/-/destroy-1.0.4.tgz",
      "integrity": "sha1-l4hXRCxEdJ5CBmE+N5RiBYJqvYA="
    },
    "detect-indent": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/detect-indent/-/detect-indent-4.0.0.tgz",
      "integrity": "sha1-920GQ1LN9Docts5hnE7jqUdd4gg=",
      "requires": {
        "repeating": "^2.0.0"
      }
    },
    "detect-newline": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/detect-newline/-/detect-newline-2.1.0.tgz",
      "integrity": "sha1-9B8cEL5LAOh7XxPaaAdZ8sW/0+I="
    },
    "dom-helpers": {
      "version": "3.4.0",
      "resolved": "https://registry.npmjs.org/dom-helpers/-/dom-helpers-3.4.0.tgz",
      "integrity": "sha512-LnuPJ+dwqKDIyotW1VzmOZ5TONUN7CwkCR5hrgawTUbkBGYdeoNLZo6nNfGkCrjtE1nXXaj7iMMpDa8/d9WoIA==",
      "requires": {
        "@babel/runtime": "^7.1.2"
      }
    },
    "dom-walk": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/dom-walk/-/dom-walk-0.1.1.tgz",
      "integrity": "sha1-ZyIm3HTI95mtNTB9+TaroRrNYBg="
    },
    "ee-first": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz",
      "integrity": "sha1-WQxhFWsK4vTwJVcyoViyZrxWsh0="
    },
    "emojis-list": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/emojis-list/-/emojis-list-2.1.0.tgz",
      "integrity": "sha1-TapNnbAPmBmIDHn6RXrlsJof04k="
    },
    "encodeurl": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/encodeurl/-/encodeurl-1.0.2.tgz",
      "integrity": "sha1-rT/0yG7C0CkyL1oCw6mmBslbP1k="
    },
    "encoding": {
      "version": "0.1.12",
      "resolved": "https://registry.npmjs.org/encoding/-/encoding-0.1.12.tgz",
      "integrity": "sha1-U4tm8+5izRq1HsMjgp0flIDHS+s=",
      "requires": {
        "iconv-lite": "~0.4.13"
      }
    },
    "envinfo": {
      "version": "5.12.1",
      "resolved": "https://registry.npmjs.org/envinfo/-/envinfo-5.12.1.tgz",
      "integrity": "sha512-pwdo0/G3CIkQ0y6PCXq4RdkvId2elvtPCJMG0konqlrfkWQbf1DWeH9K2b/cvu2YgGvPPTOnonZxXM1gikFu1w=="
    },
    "error-ex": {
      "version": "1.3.2",
      "resolved": "https://registry.npmjs.org/error-ex/-/error-ex-1.3.2.tgz",
      "integrity": "sha512-7dFHNmqeFSEt2ZBsCriorKnn3Z2pj+fd9kmI6QoWw4//DL+icEBfc0U7qJCisqrTsKTjw4fNFy2pW9OqStD84g==",
      "requires": {
        "is-arrayish": "^0.2.1"
      },
      "dependencies": {
        "is-arrayish": {
          "version": "0.2.1",
          "resolved": "https://registry.npmjs.org/is-arrayish/-/is-arrayish-0.2.1.tgz",
          "integrity": "sha1-d8mYQFJ6qOyxqLppe4BkWnqSap0="
        }
      }
    },
    "errorhandler": {
      "version": "1.5.0",
      "resolved": "https://registry.npmjs.org/errorhandler/-/errorhandler-1.5.0.tgz",
      "integrity": "sha1-6rpkyl1UKjEayUX1gt78M2Fl2fQ=",
      "requires": {
        "accepts": "~1.3.3",
        "escape-html": "~1.0.3"
      }
    },
    "escape-html": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/escape-html/-/escape-html-1.0.3.tgz",
      "integrity": "sha1-Aljq5NPQwJdN4cFpGI7wBR0dGYg="
    },
    "escape-string-regexp": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-1.0.5.tgz",
      "integrity": "sha1-G2HAViGQqN/2rjuyzwIAyhMLhtQ="
    },
    "esprima": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/esprima/-/esprima-4.0.1.tgz",
      "integrity": "sha512-eGuFFw7Upda+g4p+QHvnW0RyTX/SVeJBDM/gCtMARO0cLuT2HcEKnTPvhjV6aGeqrCB/sbNop0Kszm0jsaWU4A=="
    },
    "esutils": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/esutils/-/esutils-2.0.2.tgz",
      "integrity": "sha1-Cr9PHKpbyx96nYrMbepPqqBLrJs="
    },
    "etag": {
      "version": "1.8.1",
      "resolved": "https://registry.npmjs.org/etag/-/etag-1.8.1.tgz",
      "integrity": "sha1-Qa4u62XvpiJorr/qg6x9eSmbCIc="
    },
    "event-target-shim": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/event-target-shim/-/event-target-shim-1.1.1.tgz",
      "integrity": "sha1-qG5e5r2qFgVEddp5fM3fDFVphJE="
    },
    "eventemitter3": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/eventemitter3/-/eventemitter3-3.1.0.tgz",
      "integrity": "sha512-ivIvhpq/Y0uSjcHDcOIccjmYjGLcP09MFGE7ysAwkAvkXfpZlC985pH2/ui64DKazbTW/4kN3yqozUxlXzI6cA=="
    },
    "exec-sh": {
      "version": "0.2.2",
      "resolved": "https://registry.npmjs.org/exec-sh/-/exec-sh-0.2.2.tgz",
      "integrity": "sha512-FIUCJz1RbuS0FKTdaAafAByGS0CPvU3R0MeHxgtl+djzCc//F8HakL8GzmVNZanasTbTAY/3DRFA0KpVqj/eAw==",
      "requires": {
        "merge": "^1.2.0"
      }
    },
    "execa": {
      "version": "0.7.0",
      "resolved": "https://registry.npmjs.org/execa/-/execa-0.7.0.tgz",
      "integrity": "sha1-lEvs00zEHuMqY6n68nrVpl/Fl3c=",
      "requires": {
        "cross-spawn": "^5.0.1",
        "get-stream": "^3.0.0",
        "is-stream": "^1.1.0",
        "npm-run-path": "^2.0.0",
        "p-finally": "^1.0.0",
        "signal-exit": "^3.0.0",
        "strip-eof": "^1.0.0"
      }
    },
    "expand-brackets": {
      "version": "0.1.5",
      "resolved": "https://registry.npmjs.org/expand-brackets/-/expand-brackets-0.1.5.tgz",
      "integrity": "sha1-3wcoTjQqgHzXM6xa9yQR5YHRF3s=",
      "requires": {
        "is-posix-bracket": "^0.1.0"
      }
    },
    "expand-range": {
      "version": "1.8.2",
      "resolved": "https://registry.npmjs.org/expand-range/-/expand-range-1.8.2.tgz",
      "integrity": "sha1-opnv/TNf4nIeuujiV+x5ZE/IUzc=",
      "requires": {
        "fill-range": "^2.1.0"
      }
    },
    "expo": {
      "version": "32.0.6",
      "resolved": "https://registry.npmjs.org/expo/-/expo-32.0.6.tgz",
      "integrity": "sha512-LMFtWZY+lwMHkoThTBwirctPB/5WeZtGrVM8MVoCI1e7jlONOfNQceM6X2j06BO5HxcCF/ASJSUDiTIIStAeaA==",
      "requires": {
        "@babel/runtime": "^7.1.2",
        "@expo/vector-icons": "~9.0.0",
        "@expo/websql": "^1.0.1",
        "@types/fbemitter": "^2.0.32",
        "@types/invariant": "^2.2.29",
        "@types/lodash.zipobject": "^4.1.4",
        "@types/qs": "^6.5.1",
        "@types/uuid-js": "^0.7.1",
        "@types/websql": "^0.0.27",
        "babel-preset-expo": "^5.0.0",
        "cross-spawn": "^6.0.5",
        "expo-ads-admob": "~2.0.0",
        "expo-analytics-segment": "~2.0.0",
        "expo-app-auth": "~2.0.0",
        "expo-app-loader-provider": "~1.0.0",
        "expo-asset": "~2.0.0",
        "expo-background-fetch": "~1.0.0",
        "expo-barcode-scanner": "~2.0.0",
        "expo-barcode-scanner-interface": "~2.0.0",
        "expo-camera": "~2.0.0",
        "expo-camera-interface": "~2.0.0",
        "expo-constants": "~2.0.0",
        "expo-constants-interface": "~2.0.0",
        "expo-contacts": "~2.0.0",
        "expo-core": "~2.0.0",
        "expo-errors": "~1.0.0",
        "expo-face-detector": "~2.0.0",
        "expo-face-detector-interface": "~2.0.0",
        "expo-file-system": "~2.0.0",
        "expo-file-system-interface": "~2.0.0",
        "expo-font": "~2.0.0",
        "expo-font-interface": "~2.0.0",
        "expo-gl": "~2.0.0",
        "expo-gl-cpp": "~2.0.0",
        "expo-google-sign-in": "~2.0.0",
        "expo-image-loader-interface": "~2.0.0",
        "expo-local-authentication": "~2.0.0",
        "expo-localization": "~2.0.0",
        "expo-location": "~2.0.1",
        "expo-media-library": "~2.0.0",
        "expo-payments-stripe": "~2.0.0",
        "expo-permissions": "~2.0.0",
        "expo-permissions-interface": "~2.0.0",
        "expo-print": "~2.0.0",
        "expo-react-native-adapter": "~2.0.0",
        "expo-sensors": "~2.0.0",
        "expo-sensors-interface": "~2.0.0",
        "expo-sms": "~2.0.0",
        "expo-task-manager": "~1.0.0",
        "fbemitter": "^2.1.1",
        "invariant": "^2.2.2",
        "lodash.filter": "^4.6.0",
        "lodash.map": "^4.6.0",
        "lodash.omit": "^4.5.0",
        "lodash.zipobject": "^4.1.3",
        "lottie-react-native": "2.5.0",
        "md5-file": "^3.2.3",
        "nullthrows": "^1.1.0",
        "pretty-format": "^23.6.0",
        "prop-types": "^15.6.0",
        "qs": "^6.5.0",
        "react-native-branch": "2.2.5",
        "react-native-gesture-handler": "~1.0.14",
        "react-native-reanimated": "1.0.0-alpha.11",
        "react-native-screens": "1.0.0-alpha.22",
        "react-native-svg": "8.0.10",
        "react-native-view-shot": "2.5.0",
        "serialize-error": "^2.1.0",
        "uuid-js": "^0.7.5",
        "whatwg-fetch": "^2.0.4"
      },
      "dependencies": {
        "cross-spawn": {
          "version": "6.0.5",
          "resolved": "https://registry.npmjs.org/cross-spawn/-/cross-spawn-6.0.5.tgz",
          "integrity": "sha512-eTVLrBSt7fjbDygz805pMnstIs2VTBNkRm0qxZd+M7A5XDdxVRWO5MxGBXZhjY4cqLYLdtrGqRf8mBPmzwSpWQ==",
          "requires": {
            "nice-try": "^1.0.4",
            "path-key": "^2.0.1",
            "semver": "^5.5.0",
            "shebang-command": "^1.2.0",
            "which": "^1.2.9"
          },
          "dependencies": {
            "nice-try": {
              "version": "1.0.5",
              "resolved": "https://registry.npmjs.org/nice-try/-/nice-try-1.0.5.tgz",
              "integrity": "sha512-1nh45deeb5olNY7eX82BkPO7SSxR5SSYJiPTrTdFUVYwAl8CKMA5N9PjTYkHiRjisVcxcQ1HXdLhx2qxxJzLNQ=="
            }
          }
        },
        "react-native-maps": {
          "version": "github:expo/react-native-maps#e6f98ff7272e5d0a7fe974a41f28593af2d77bb2",
          "from": "github:expo/react-native-maps#e6f98ff7272e5d0a7fe974a41f28593af2d77bb2"
        }
      }
    },
    "expo-ads-admob": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-ads-admob/-/expo-ads-admob-2.0.0.tgz",
      "integrity": "sha512-mGx4rDBlDgVRf0jKsl4IpghBDG7vphriUmGa6BYRjnwc7PaQJMeQOINxQKLr37CvTuzvhiDz+yYFBeS5baRNXg==",
      "requires": {
        "prop-types": "^15.6.2"
      }
    },
    "expo-analytics-segment": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-analytics-segment/-/expo-analytics-segment-2.0.0.tgz",
      "integrity": "sha512-NSqvm1bK0cxnBXwypkfQc1ZM8jE5ARgSs1PYgxqsyEDY1ivxJkpvf0R0QOxqHjG4N34ox0J3YJHRCLHyMyrRbA==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "expo-app-auth": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-app-auth/-/expo-app-auth-2.0.0.tgz",
      "integrity": "sha512-g3U0+G2nwgcTiINTAS3FtQvvLfOm9ZMeUDJ6rc6YkG7JmcW6vC0s3QURYlF33UdqWeN4VUYw7o0zP6r4jsZhNQ==",
      "requires": {
        "expo-constants-interface": "~2.0.0",
        "expo-core": "~2.0.0"
      }
    },
    "expo-app-loader-provider": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/expo-app-loader-provider/-/expo-app-loader-provider-1.0.0.tgz",
      "integrity": "sha512-PAQnlGNQLO6k+k+kgGyqw4oaLS6GAvRwZRG1BofYBvcIzhZf24Nys7DuA6JT5Ukb1FtO8c5Ioi4C7pKntYiPdw==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "expo-asset": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-asset/-/expo-asset-2.0.0.tgz",
      "integrity": "sha512-8E/vQ/grJl1OX2lkzChbQJWsynIRupkxR0r8RMJ0js+MfDtmyi3m4lVzY4AjUz/y7KJ9XpldKjsqerFWb/Nmew==",
      "requires": {
        "uri-parser": "^1.0.1",
        "url-join": "^4.0.0",
        "url-loader": "^1.1.2"
      }
    },
    "expo-background-fetch": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/expo-background-fetch/-/expo-background-fetch-1.0.0.tgz",
      "integrity": "sha512-oQY2gCEZIka1xKlkW0y3/GYobdXDl9Q3//sfogLlxVcoTFScLRYCwTOBVb6RsCzLwv/CzZedbR+1WjlvKshS6Q==",
      "requires": {
        "expo-task-manager": "~1.0.0"
      }
    },
    "expo-barcode-scanner": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-barcode-scanner/-/expo-barcode-scanner-2.0.0.tgz",
      "integrity": "sha512-ryWfpqpw+gzvZVfsm6IUj6oSi22sWeuEg7j38Vn0C9LoHVWNt93JcKWTulO+8Pk2iThvr/ernmHqyMGatwmv6g==",
      "requires": {
        "expo-barcode-scanner-interface": "~2.0.0",
        "lodash.mapvalues": "^4.6.0",
        "prop-types": "^15.6.0"
      }
    },
    "expo-barcode-scanner-interface": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-barcode-scanner-interface/-/expo-barcode-scanner-interface-2.0.0.tgz",
      "integrity": "sha512-rfCLqL06zVcyT5usKBQqDA0ilIEYv5zi91lUJ6s2/Llvx/OHuiPY4w1ol5HJPRJQvaBHop3lXqnb7dUuEMTsIA=="
    },
    "expo-camera": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-camera/-/expo-camera-2.0.0.tgz",
      "integrity": "sha512-TVRuMMQ8+Y54v7Q3Wls3ZXABMhA+W7u5M3Ghdmc6hPUVubG1TprAk257BorfaI09QJ5jOevDzdw3IAFEvyE+Pg==",
      "requires": {
        "lodash.mapvalues": "^4.6.0",
        "prop-types": "^15.6.0"
      }
    },
    "expo-camera-interface": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-camera-interface/-/expo-camera-interface-2.0.0.tgz",
      "integrity": "sha512-6CLexDa/RhrJ74dzNKyg7aHcNG11FH/F83sD+wIbhoE7fm3FGEbSXxOKccWmVAUApMyn3Sdev4MLjnKUX0opBQ==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "expo-constants": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/expo-constants/-/expo-constants-2.0.1.tgz",
      "integrity": "sha512-OIT1afOYYSpDxnnTp5jNXNB2nfnbmykLT+fLaKTu60VdtrO0sr20eB30YwuALU7n/xSYM/xKPsP8jDCzq40YLw==",
      "requires": {
        "ua-parser-js": "^0.7.19",
        "uuid": "^3.3.2"
      },
      "dependencies": {
        "uuid": {
          "version": "3.3.2",
          "resolved": "https://registry.npmjs.org/uuid/-/uuid-3.3.2.tgz",
          "integrity": "sha512-yXJmeNaw3DnnKAOKJE51sL/ZaYfWJRl1pK9dr19YFCu0ObS231AB1/LbqTKRAQ5kw8A90rA6fr4riOUpTZvQZA=="
        }
      }
    },
    "expo-constants-interface": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-constants-interface/-/expo-constants-interface-2.0.0.tgz",
      "integrity": "sha512-H5qXLl1Ew+Aemo127B9zvdtutYCZRwYnb1wRY2gKvECuyHTfRylld7fA6otebNf1NwqCQ5bowTZtls4SKWxTiQ==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "expo-contacts": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-contacts/-/expo-contacts-2.0.0.tgz",
      "integrity": "sha512-aRq8WZ9XeTffI8vidS2Yu51WqIRsj+oWt2kaFPCnGHeH71eE6HxuNapQGe+RmoyJmpntVHYdlg3kAgyW84odQw==",
      "requires": {
        "expo-core": "~2.0.0",
        "expo-errors": "~1.0.0",
        "uuid-js": "^0.7.5"
      }
    },
    "expo-core": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/expo-core/-/expo-core-2.0.1.tgz",
      "integrity": "sha512-BmQqSHThhnI2xSEWFm4J0uQv5iATwLcY2A0pArjUOT+JK0h2V3x2lt0EZFekjrKwZwIPOwyEYFO1Drzn41Oxsg=="
    },
    "expo-errors": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/expo-errors/-/expo-errors-1.0.0.tgz",
      "integrity": "sha512-4CL/75aigg+pYwgR+7SUJwYgX2oa7ZGAwK1aYKnyUnwQOa9jmjJJoT9KPHO8SbDHz+mEwjD5TE8ZXfOWlMl+kw==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "expo-face-detector": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-face-detector/-/expo-face-detector-2.0.0.tgz",
      "integrity": "sha512-w+pO6AURNNZt0ocqHPFHR6EQ2ZyZorSkwRCCZoLLm7GZ1PdMLIRfkqeN1hAWmHcGt9sEzRBaYWJETzDtwSd4BA==",
      "requires": {
        "expo-core": "~2.0.0",
        "expo-face-detector-interface": "~2.0.0",
        "expo-permissions-interface": "~2.0.0"
      }
    },
    "expo-face-detector-interface": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-face-detector-interface/-/expo-face-detector-interface-2.0.0.tgz",
      "integrity": "sha512-BXBxTMFy2YFANWxxgXmrie2R68ATv2KJJ9iaVYCNSoAXplAsHF+Kc2hkVBLE/xAU2+QFzVq9N21CVOIfKsWN4A==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "expo-file-system": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-file-system/-/expo-file-system-2.0.0.tgz",
      "integrity": "sha512-snYf1kIYB9Jx2z1Vsj7+q3SSKyjmWPH+dpWlxCS+gHRgFzWI36y46SZCL/d76SmM2SOMhS95mIU+EZR7rKSJTQ==",
      "requires": {
        "expo-core": "~2.0.0",
        "expo-file-system-interface": "~2.0.0",
        "uuid-js": "^0.7.5"
      }
    },
    "expo-file-system-interface": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-file-system-interface/-/expo-file-system-interface-2.0.0.tgz",
      "integrity": "sha512-lhNjfPyNspQIJOqDM/Z8lpFICc0QF/Ah1DtYCDeQSng/zgAaLlRyDN3vSb/a5NrluSDfRlU2oF2sbrxIsOzzbg==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "expo-font": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-font/-/expo-font-2.0.0.tgz",
      "integrity": "sha512-0o79ON0aQQCcA3OXXnRllGGnFFfDXXe2QB/IIGrksD5UL8MPwhLWAsD3ZsZJYgo3H6tE/i8moB2zQ1i2Q/4pNg==",
      "requires": {
        "invariant": "^2.2.2"
      }
    },
    "expo-font-interface": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-font-interface/-/expo-font-interface-2.0.0.tgz",
      "integrity": "sha512-5tEGjUwOLd5h6vTR3xfNc6jXTRKzLVnGpIjns+L2aArIIktmlZU3Y/gzueY8AkB6J6SB5DYSLlybp5kQrUOImw==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "expo-gl": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-gl/-/expo-gl-2.0.0.tgz",
      "integrity": "sha512-iCzaBXvV/YIfPUTAZrI6TDdQDp3qPOCKfib8L/haAjXLf74SqDevQzLFSTfahGZJRgR9/NXsVfKc0z6MmTeIZw==",
      "requires": {
        "prop-types": "^15.6.2"
      }
    },
    "expo-gl-cpp": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-gl-cpp/-/expo-gl-cpp-2.0.0.tgz",
      "integrity": "sha512-Vuj/ABhqOQgdFFJjGEzZ9soFEHGbwOzL6T9oH70osrl4laep/4RCtQy80zThC0aNRDFFmh5923SyqBo5CGKJyQ==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "expo-google-sign-in": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-google-sign-in/-/expo-google-sign-in-2.0.0.tgz",
      "integrity": "sha512-2uuHbKQov4e+oITVBj/TyUhGqyP2hCEGRMqzHc1POb47z7J3yfVordAxdost4sazrWkWRrOHMAJp6Xah38d5pQ==",
      "requires": {
        "expo-errors": "~1.0.0",
        "invariant": "^2.2.4"
      }
    },
    "expo-image-loader-interface": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-image-loader-interface/-/expo-image-loader-interface-2.0.0.tgz",
      "integrity": "sha512-aOHa37N/8gEyzDGO5df6PST8uce1L94OxNTfD5JtWVH3tWmkaN760S33T9ecWmydcUv9zFCOcCC4gZTwEWUJiQ==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "expo-local-authentication": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-local-authentication/-/expo-local-authentication-2.0.0.tgz",
      "integrity": "sha512-okW+EeLXgIG6xNfxl99bjJDrzmrx44fzYmSRKFspCH6JJQNqGFUgyMjqOsiSlEjPxr3S7Y2aYU0pHgoeoajGjw==",
      "requires": {
        "expo-core": "~2.0.0",
        "invariant": "^2.2.4"
      }
    },
    "expo-localization": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-localization/-/expo-localization-2.0.0.tgz",
      "integrity": "sha512-QDs76ZWi8zf/Zbt9EG/ToQ8qQv3Z8GsjPVFT3J0idikpuMIPhqKSZLYOkiXpTuOhh5I1CGfIiXCqkQX77n8l7A==",
      "requires": {
        "expo-core": "~2.0.0",
        "moment": "^2.22.2",
        "moment-timezone": "^0.5.23",
        "rtl-detect": "^1.0.2"
      }
    },
    "expo-location": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/expo-location/-/expo-location-2.0.1.tgz",
      "integrity": "sha512-hd1lZ1yPh+q50AihNqdeAumr3R64fp7qKlJ/5Ry1ap519Gy3uA1y+XOw5HHNXDw+/fbO9O1xBLpAuJUbZxVk8w==",
      "requires": {
        "invariant": "^2.2.4"
      }
    },
    "expo-media-library": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-media-library/-/expo-media-library-2.0.0.tgz",
      "integrity": "sha512-o6zQEuanRYFIh2z74B5NhZQdCAZPRTBLFnGB5ZUfdiAXjrN5gnn9tY+7vYyNJcS4uxd7r7sVK+2l2QP14EsPMg==",
      "requires": {
        "expo-core": "~2.0.0",
        "expo-errors": "~1.0.0",
        "expo-permissions-interface": "~2.0.0"
      }
    },
    "expo-payments-stripe": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-payments-stripe/-/expo-payments-stripe-2.0.0.tgz",
      "integrity": "sha512-13xMfo7vmFnfWvt5TihqN2baEUBCHztk4DBX3vOhjUU/dpgUcLX+jQUFVQNduYxlOk7nFW/z7GiByjqVkkOd0Q==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "expo-permissions": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-permissions/-/expo-permissions-2.0.0.tgz",
      "integrity": "sha512-0niegCTjcNdLk/715VqG5ibnT45eRGRebgdjTk/HtFOLjFtMs2mQKpneF3BbwVAK88bCbAiwtSBNt21/C+6z7A==",
      "requires": {
        "expo-core": "~2.0.0",
        "expo-permissions-interface": "~2.0.0"
      }
    },
    "expo-permissions-interface": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-permissions-interface/-/expo-permissions-interface-2.0.0.tgz",
      "integrity": "sha512-hk9oR6CtV2MLONdtPkKvOfpfmbJ48BDbYjvW/Na31znVvUAPHs7owckqSgh5BVoIAz8tMgp7fptaifEhPOayvg==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "expo-print": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-print/-/expo-print-2.0.0.tgz",
      "integrity": "sha512-wTzqIxaNb7qq+2P+y8Yf/umfqDJQnXYCf9Ns046pFOeybHd1r3pJRy6A9Myc2tFeNA2/xSx8oICMmqO1ZNRPLQ==",
      "requires": {
        "babel-preset-expo": "^5.0.0",
        "expo-core": "~2.0.0",
        "expo-errors": "~1.0.0"
      }
    },
    "expo-react-native-adapter": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-react-native-adapter/-/expo-react-native-adapter-2.0.0.tgz",
      "integrity": "sha512-pRlmqqb9mPr1abgzEGnzeEWa7VI8WWqMWRnU/ySJTcOWRyX63oUobTKX/Bw1HuwGyB6+rVRqEF+IObOeo8va4w==",
      "requires": {
        "expo-image-loader-interface": "~2.0.0",
        "expo-permissions-interface": "~2.0.0",
        "invariant": "^2.2.4",
        "lodash.omit": "^4.5.0",
        "lodash.pick": "^4.4.0",
        "prop-types": "^15.6.1"
      }
    },
    "expo-sensors": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-sensors/-/expo-sensors-2.0.0.tgz",
      "integrity": "sha512-qr5n+gXKmmXL4LCAXygeafIHxzOLfepewsnVS2ZJJ3ARNdhH6bWpgXLOxJH8482O21sV/dGFn0DG/lbuiyBxeg==",
      "requires": {
        "invariant": "^2.2.4"
      }
    },
    "expo-sensors-interface": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-sensors-interface/-/expo-sensors-interface-2.0.0.tgz",
      "integrity": "sha512-Lx5j4xeBxPHPxc1ySL3EZqr0PtJAdNaHu/uEj4OkrvWfE8QfyN/dS8j8x7vtdHZmwlBONWev2dL5Kpojzo7DEQ==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "expo-sms": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/expo-sms/-/expo-sms-2.0.0.tgz",
      "integrity": "sha512-kQ7VnBHjz0B2OyfM100daLWwOvGQ88Tm1q75RPiYN/miry/3mpXriFDbvMnF8EH6G7UlfdrVTIdV63HuYyhNmA==",
      "requires": {
        "expo-core": "~2.0.0",
        "expo-permissions-interface": "~2.0.0"
      }
    },
    "expo-task-manager": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/expo-task-manager/-/expo-task-manager-1.0.0.tgz",
      "integrity": "sha512-ySm4K9JNl+Yw5BAdatJdc0A3rV8Bp2PT6R3P0M7q6P6jkbscn+NJ7VAVzu05ID8MY8yGGSZHyzRjScEW7/lskA==",
      "requires": {
        "expo-core": "~2.0.0",
        "expo-errors": "~1.0.0",
        "expo-task-manager-interface": "~1.0.0"
      }
    },
    "expo-task-manager-interface": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/expo-task-manager-interface/-/expo-task-manager-interface-1.0.0.tgz",
      "integrity": "sha512-ly+LK55Yyx/jFQN4ZQsRFFn5JGAczY6nPNMV1iTxxK7o6I1hv2ZO9DAzYQpU41VIoPNDsSO/5JAh0HWV44MlsA==",
      "requires": {
        "expo-core": "~2.0.0"
      }
    },
    "extend-shallow": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-1.1.4.tgz",
      "integrity": "sha1-Gda/lN/AnXa6cR85uHLSH/TdkHE=",
      "requires": {
        "kind-of": "^1.1.0"
      }
    },
    "external-editor": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/external-editor/-/external-editor-2.2.0.tgz",
      "integrity": "sha512-bSn6gvGxKt+b7+6TKEv1ZycHleA7aHhRHyAqJyp5pbUFuYYNIzpZnQDk7AsYckyWdEnTeAnay0aCy2aV6iTk9A==",
      "requires": {
        "chardet": "^0.4.0",
        "iconv-lite": "^0.4.17",
        "tmp": "^0.0.33"
      }
    },
    "extglob": {
      "version": "0.3.2",
      "resolved": "https://registry.npmjs.org/extglob/-/extglob-0.3.2.tgz",
      "integrity": "sha1-Lhj/PS9JqydlzskCPwEdqo2DSaE=",
      "requires": {
        "is-extglob": "^1.0.0"
      }
    },
    "fancy-log": {
      "version": "1.3.3",
      "resolved": "https://registry.npmjs.org/fancy-log/-/fancy-log-1.3.3.tgz",
      "integrity": "sha512-k9oEhlyc0FrVh25qYuSELjr8oxsCoc4/LEZfg2iJJrfEk/tZL9bCoJE47gqAvI2m/AUjluCS4+3I0eTx8n3AEw==",
      "requires": {
        "ansi-gray": "^0.1.1",
        "color-support": "^1.1.3",
        "parse-node-version": "^1.0.0",
        "time-stamp": "^1.0.0"
      }
    },
    "fast-deep-equal": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/fast-deep-equal/-/fast-deep-equal-2.0.1.tgz",
      "integrity": "sha1-ewUhjd+WZ79/Nwv3/bLLFf3Qqkk="
    },
    "fast-json-stable-stringify": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/fast-json-stable-stringify/-/fast-json-stable-stringify-2.0.0.tgz",
      "integrity": "sha1-1RQsDK7msRifh9OnYREGT4bIu/I="
    },
    "fb-watchman": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/fb-watchman/-/fb-watchman-2.0.0.tgz",
      "integrity": "sha1-VOmr99+i8mzZsWNsWIwa/AXeXVg=",
      "requires": {
        "bser": "^2.0.0"
      }
    },
    "fbemitter": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/fbemitter/-/fbemitter-2.1.1.tgz",
      "integrity": "sha1-Uj4U/a9SSIBbsC9i78M75wP1GGU=",
      "requires": {
        "fbjs": "^0.8.4"
      }
    },
    "fbjs": {
      "version": "0.8.17",
      "resolved": "https://registry.npmjs.org/fbjs/-/fbjs-0.8.17.tgz",
      "integrity": "sha1-xNWY6taUkRJlPWWIsBpc3Nn5D90=",
      "requires": {
        "core-js": "^1.0.0",
        "isomorphic-fetch": "^2.1.1",
        "loose-envify": "^1.0.0",
        "object-assign": "^4.1.0",
        "promise": "^7.1.1",
        "setimmediate": "^1.0.5",
        "ua-parser-js": "^0.7.18"
      },
      "dependencies": {
        "core-js": {
          "version": "1.2.7",
          "resolved": "https://registry.npmjs.org/core-js/-/core-js-1.2.7.tgz",
          "integrity": "sha1-ZSKUwUZR2yj6k70tX/KYOk8IxjY="
        }
      }
    },
    "fbjs-scripts": {
      "version": "0.8.3",
      "resolved": "https://registry.npmjs.org/fbjs-scripts/-/fbjs-scripts-0.8.3.tgz",
      "integrity": "sha512-aUJ/uEzMIiBYuj/blLp4sVNkQQ7ZEB/lyplG1IzzOmZ83meiWecrGg5jBo4wWrxXmO4RExdtsSV1QkTjPt2Gag==",
      "requires": {
        "ansi-colors": "^1.0.1",
        "babel-core": "^6.7.2",
        "babel-preset-fbjs": "^2.1.2",
        "core-js": "^2.4.1",
        "cross-spawn": "^5.1.0",
        "fancy-log": "^1.3.2",
        "object-assign": "^4.0.1",
        "plugin-error": "^0.1.2",
        "semver": "^5.1.0",
        "through2": "^2.0.0"
      }
    },
    "figures": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/figures/-/figures-2.0.0.tgz",
      "integrity": "sha1-OrGi0qYsi/tDGgyUy3l6L84nyWI=",
      "requires": {
        "escape-string-regexp": "^1.0.5"
      }
    },
    "filename-regex": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/filename-regex/-/filename-regex-2.0.1.tgz",
      "integrity": "sha1-wcS5vuPglyXdsQa3XB4wH+LxiyY="
    },
    "fill-range": {
      "version": "2.2.4",
      "resolved": "https://registry.npmjs.org/fill-range/-/fill-range-2.2.4.tgz",
      "integrity": "sha512-cnrcCbj01+j2gTG921VZPnHbjmdAf8oQV/iGeV2kZxGSyfYjjTyY79ErsK1WJWMpw6DaApEX72binqJE+/d+5Q==",
      "requires": {
        "is-number": "^2.1.0",
        "isobject": "^2.0.0",
        "randomatic": "^3.0.0",
        "repeat-element": "^1.1.2",
        "repeat-string": "^1.5.2"
      }
    },
    "finalhandler": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/finalhandler/-/finalhandler-1.1.0.tgz",
      "integrity": "sha1-zgtoVbRYU+eRsvzGgARtiCU91/U=",
      "requires": {
        "debug": "2.6.9",
        "encodeurl": "~1.0.1",
        "escape-html": "~1.0.3",
        "on-finished": "~2.3.0",
        "parseurl": "~1.3.2",
        "statuses": "~1.3.1",
        "unpipe": "~1.0.0"
      }
    },
    "find-babel-config": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/find-babel-config/-/find-babel-config-1.1.0.tgz",
      "integrity": "sha1-rMAQQ6Z0n+w0Qpvmtk9ULrtdY1U=",
      "requires": {
        "json5": "^0.5.1",
        "path-exists": "^3.0.0"
      }
    },
    "find-cache-dir": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/find-cache-dir/-/find-cache-dir-1.0.0.tgz",
      "integrity": "sha1-kojj6ePMN0hxfTnq3hfPcfww7m8=",
      "requires": {
        "commondir": "^1.0.1",
        "make-dir": "^1.0.0",
        "pkg-dir": "^2.0.0"
      }
    },
    "find-up": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/find-up/-/find-up-2.1.0.tgz",
      "integrity": "sha1-RdG35QbHF93UgndaK3eSCjwMV6c=",
      "requires": {
        "locate-path": "^2.0.0"
      }
    },
    "fn-name": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/fn-name/-/fn-name-2.0.1.tgz",
      "integrity": "sha1-UhTXU3pNBqSjAcDMJi/rhBiAAuc="
    },
    "for-in": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/for-in/-/for-in-1.0.2.tgz",
      "integrity": "sha1-gQaNKVqBQuwKxybG4iAMMPttXoA="
    },
    "for-own": {
      "version": "0.1.5",
      "resolved": "https://registry.npmjs.org/for-own/-/for-own-0.1.5.tgz",
      "integrity": "sha1-UmXGgaTylNq78XyVCbZ2OqhFEM4=",
      "requires": {
        "for-in": "^1.0.1"
      }
    },
    "formik": {
      "version": "1.5.1",
      "resolved": "https://registry.npmjs.org/formik/-/formik-1.5.1.tgz",
      "integrity": "sha512-FBWGBKQkcCE4d5b5l2fKccD9d1QxNxw/0bQTRvp3EjzA8Bnjmsm9H/Oy0375UA8P3FPmfJkF4cXLLdEqK7fP5A==",
      "requires": {
        "create-react-context": "^0.2.2",
        "deepmerge": "^2.1.1",
        "hoist-non-react-statics": "^2.5.5",
        "lodash": "^4.17.11",
        "lodash-es": "^4.17.11",
        "prop-types": "^15.6.1",
        "react-fast-compare": "^2.0.1",
        "tiny-warning": "^1.0.2",
        "tslib": "^1.9.3"
      }
    },
    "fragment-cache": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/fragment-cache/-/fragment-cache-0.2.1.tgz",
      "integrity": "sha1-QpD60n8T6Jvn8zeZxrxaCr//DRk=",
      "requires": {
        "map-cache": "^0.2.2"
      }
    },
    "fresh": {
      "version": "0.5.2",
      "resolved": "https://registry.npmjs.org/fresh/-/fresh-0.5.2.tgz",
      "integrity": "sha1-PYyt2Q2XZWn6g1qx+OSyOhBWBac="
    },
    "fs-extra": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/fs-extra/-/fs-extra-1.0.0.tgz",
      "integrity": "sha1-zTzl9+fLYUWIP8rjGR6Yd/hYeVA=",
      "requires": {
        "graceful-fs": "^4.1.2",
        "jsonfile": "^2.1.0",
        "klaw": "^1.0.0"
      }
    },
    "fs.realpath": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz",
      "integrity": "sha1-FQStJSMVjKpA20onh8sBQRmU6k8="
    },
    "fsevents": {
      "version": "1.2.7",
      "resolved": "https://registry.npmjs.org/fsevents/-/fsevents-1.2.7.tgz",
      "integrity": "sha512-Pxm6sI2MeBD7RdD12RYsqaP0nMiwx8eZBXCa6z2L+mRHm2DYrOYwihmhjpkdjUHwQhslWQjRpEgNq4XvBmaAuw==",
      "optional": true,
      "requires": {
        "nan": "^2.9.2",
        "node-pre-gyp": "^0.10.0"
      },
      "dependencies": {
        "abbrev": {
          "version": "1.1.1",
          "bundled": true,
          "optional": true
        },
        "ansi-regex": {
          "version": "2.1.1",
          "bundled": true,
          "optional": true
        },
        "aproba": {
          "version": "1.2.0",
          "bundled": true,
          "optional": true
        },
        "are-we-there-yet": {
          "version": "1.1.5",
          "bundled": true,
          "optional": true,
          "requires": {
            "delegates": "^1.0.0",
            "readable-stream": "^2.0.6"
          }
        },
        "balanced-match": {
          "version": "1.0.0",
          "bundled": true,
          "optional": true
        },
        "brace-expansion": {
          "version": "1.1.11",
          "bundled": true,
          "optional": true,
          "requires": {
            "balanced-match": "^1.0.0",
            "concat-map": "0.0.1"
          }
        },
        "chownr": {
          "version": "1.1.1",
          "bundled": true,
          "optional": true
        },
        "code-point-at": {
          "version": "1.1.0",
          "bundled": true,
          "optional": true
        },
        "concat-map": {
          "version": "0.0.1",
          "bundled": true,
          "optional": true
        },
        "console-control-strings": {
          "version": "1.1.0",
          "bundled": true,
          "optional": true
        },
        "core-util-is": {
          "version": "1.0.2",
          "bundled": true,
          "optional": true
        },
        "debug": {
          "version": "2.6.9",
          "bundled": true,
          "optional": true,
          "requires": {
            "ms": "2.0.0"
          }
        },
        "deep-extend": {
          "version": "0.6.0",
          "bundled": true,
          "optional": true
        },
        "delegates": {
          "version": "1.0.0",
          "bundled": true,
          "optional": true
        },
        "detect-libc": {
          "version": "1.0.3",
          "bundled": true,
          "optional": true
        },
        "fs-minipass": {
          "version": "1.2.5",
          "bundled": true,
          "optional": true,
          "requires": {
            "minipass": "^2.2.1"
          }
        },
        "fs.realpath": {
          "version": "1.0.0",
          "bundled": true,
          "optional": true
        },
        "gauge": {
          "version": "2.7.4",
          "bundled": true,
          "optional": true,
          "requires": {
            "aproba": "^1.0.3",
            "console-control-strings": "^1.0.0",
            "has-unicode": "^2.0.0",
            "object-assign": "^4.1.0",
            "signal-exit": "^3.0.0",
            "string-width": "^1.0.1",
            "strip-ansi": "^3.0.1",
            "wide-align": "^1.1.0"
          }
        },
        "glob": {
          "version": "7.1.3",
          "bundled": true,
          "optional": true,
          "requires": {
            "fs.realpath": "^1.0.0",
            "inflight": "^1.0.4",
            "inherits": "2",
            "minimatch": "^3.0.4",
            "once": "^1.3.0",
            "path-is-absolute": "^1.0.0"
          }
        },
        "has-unicode": {
          "version": "2.0.1",
          "bundled": true,
          "optional": true
        },
        "iconv-lite": {
          "version": "0.4.24",
          "bundled": true,
          "optional": true,
          "requires": {
            "safer-buffer": ">= 2.1.2 < 3"
          }
        },
        "ignore-walk": {
          "version": "3.0.1",
          "bundled": true,
          "optional": true,
          "requires": {
            "minimatch": "^3.0.4"
          }
        },
        "inflight": {
          "version": "1.0.6",
          "bundled": true,
          "optional": true,
          "requires": {
            "once": "^1.3.0",
            "wrappy": "1"
          }
        },
        "inherits": {
          "version": "2.0.3",
          "bundled": true,
          "optional": true
        },
        "ini": {
          "version": "1.3.5",
          "bundled": true,
          "optional": true
        },
        "is-fullwidth-code-point": {
          "version": "1.0.0",
          "bundled": true,
          "optional": true,
          "requires": {
            "number-is-nan": "^1.0.0"
          }
        },
        "isarray": {
          "version": "1.0.0",
          "bundled": true,
          "optional": true
        },
        "minimatch": {
          "version": "3.0.4",
          "bundled": true,
          "optional": true,
          "requires": {
            "brace-expansion": "^1.1.7"
          }
        },
        "minimist": {
          "version": "0.0.8",
          "bundled": true,
          "optional": true
        },
        "minipass": {
          "version": "2.3.5",
          "bundled": true,
          "optional": true,
          "requires": {
            "safe-buffer": "^5.1.2",
            "yallist": "^3.0.0"
          }
        },
        "minizlib": {
          "version": "1.2.1",
          "bundled": true,
          "optional": true,
          "requires": {
            "minipass": "^2.2.1"
          }
        },
        "mkdirp": {
          "version": "0.5.1",
          "bundled": true,
          "optional": true,
          "requires": {
            "minimist": "0.0.8"
          }
        },
        "ms": {
          "version": "2.0.0",
          "bundled": true,
          "optional": true
        },
        "needle": {
          "version": "2.2.4",
          "bundled": true,
          "optional": true,
          "requires": {
            "debug": "^2.1.2",
            "iconv-lite": "^0.4.4",
            "sax": "^1.2.4"
          }
        },
        "node-pre-gyp": {
          "version": "0.10.3",
          "bundled": true,
          "optional": true,
          "requires": {
            "detect-libc": "^1.0.2",
            "mkdirp": "^0.5.1",
            "needle": "^2.2.1",
            "nopt": "^4.0.1",
            "npm-packlist": "^1.1.6",
            "npmlog": "^4.0.2",
            "rc": "^1.2.7",
            "rimraf": "^2.6.1",
            "semver": "^5.3.0",
            "tar": "^4"
          }
        },
        "nopt": {
          "version": "4.0.1",
          "bundled": true,
          "optional": true,
          "requires": {
            "abbrev": "1",
            "osenv": "^0.1.4"
          }
        },
        "npm-bundled": {
          "version": "1.0.5",
          "bundled": true,
          "optional": true
        },
        "npm-packlist": {
          "version": "1.2.0",
          "bundled": true,
          "optional": true,
          "requires": {
            "ignore-walk": "^3.0.1",
            "npm-bundled": "^1.0.1"
          }
        },
        "npmlog": {
          "version": "4.1.2",
          "bundled": true,
          "optional": true,
          "requires": {
            "are-we-there-yet": "~1.1.2",
            "console-control-strings": "~1.1.0",
            "gauge": "~2.7.3",
            "set-blocking": "~2.0.0"
          }
        },
        "number-is-nan": {
          "version": "1.0.1",
          "bundled": true,
          "optional": true
        },
        "object-assign": {
          "version": "4.1.1",
          "bundled": true,
          "optional": true
        },
        "once": {
          "version": "1.4.0",
          "bundled": true,
          "optional": true,
          "requires": {
            "wrappy": "1"
          }
        },
        "os-homedir": {
          "version": "1.0.2",
          "bundled": true,
          "optional": true
        },
        "os-tmpdir": {
          "version": "1.0.2",
          "bundled": true,
          "optional": true
        },
        "osenv": {
          "version": "0.1.5",
          "bundled": true,
          "optional": true,
          "requires": {
            "os-homedir": "^1.0.0",
            "os-tmpdir": "^1.0.0"
          }
        },
        "path-is-absolute": {
          "version": "1.0.1",
          "bundled": true,
          "optional": true
        },
        "process-nextick-args": {
          "version": "2.0.0",
          "bundled": true,
          "optional": true
        },
        "rc": {
          "version": "1.2.8",
          "bundled": true,
          "optional": true,
          "requires": {
            "deep-extend": "^0.6.0",
            "ini": "~1.3.0",
            "minimist": "^1.2.0",
            "strip-json-comments": "~2.0.1"
          },
          "dependencies": {
            "minimist": {
              "version": "1.2.0",
              "bundled": true,
              "optional": true
            }
          }
        },
        "readable-stream": {
          "version": "2.3.6",
          "bundled": true,
          "optional": true,
          "requires": {
            "core-util-is": "~1.0.0",
            "inherits": "~2.0.3",
            "isarray": "~1.0.0",
            "process-nextick-args": "~2.0.0",
            "safe-buffer": "~5.1.1",
            "string_decoder": "~1.1.1",
            "util-deprecate": "~1.0.1"
          }
        },
        "rimraf": {
          "version": "2.6.3",
          "bundled": true,
          "optional": true,
          "requires": {
            "glob": "^7.1.3"
          }
        },
        "safe-buffer": {
          "version": "5.1.2",
          "bundled": true,
          "optional": true
        },
        "safer-buffer": {
          "version": "2.1.2",
          "bundled": true,
          "optional": true
        },
        "sax": {
          "version": "1.2.4",
          "bundled": true,
          "optional": true
        },
        "semver": {
          "version": "5.6.0",
          "bundled": true,
          "optional": true
        },
        "set-blocking": {
          "version": "2.0.0",
          "bundled": true,
          "optional": true
        },
        "signal-exit": {
          "version": "3.0.2",
          "bundled": true,
          "optional": true
        },
        "string-width": {
          "version": "1.0.2",
          "bundled": true,
          "optional": true,
          "requires": {
            "code-point-at": "^1.0.0",
            "is-fullwidth-code-point": "^1.0.0",
            "strip-ansi": "^3.0.0"
          }
        },
        "string_decoder": {
          "version": "1.1.1",
          "bundled": true,
          "optional": true,
          "requires": {
            "safe-buffer": "~5.1.0"
          }
        },
        "strip-ansi": {
          "version": "3.0.1",
          "bundled": true,
          "optional": true,
          "requires": {
            "ansi-regex": "^2.0.0"
          }
        },
        "strip-json-comments": {
          "version": "2.0.1",
          "bundled": true,
          "optional": true
        },
        "tar": {
          "version": "4.4.8",
          "bundled": true,
          "optional": true,
          "requires": {
            "chownr": "^1.1.1",
            "fs-minipass": "^1.2.5",
            "minipass": "^2.3.4",
            "minizlib": "^1.1.1",
            "mkdirp": "^0.5.0",
            "safe-buffer": "^5.1.2",
            "yallist": "^3.0.2"
          }
        },
        "util-deprecate": {
          "version": "1.0.2",
          "bundled": true,
          "optional": true
        },
        "wide-align": {
          "version": "1.1.3",
          "bundled": true,
          "optional": true,
          "requires": {
            "string-width": "^1.0.2 || 2"
          }
        },
        "wrappy": {
          "version": "1.0.2",
          "bundled": true,
          "optional": true
        },
        "yallist": {
          "version": "3.0.3",
          "bundled": true,
          "optional": true
        }
      }
    },
    "gauge": {
      "version": "1.2.7",
      "resolved": "https://registry.npmjs.org/gauge/-/gauge-1.2.7.tgz",
      "integrity": "sha1-6c7FSD09TuDvRLYKfZnkk14TbZM=",
      "requires": {
        "ansi": "^0.3.0",
        "has-unicode": "^2.0.0",
        "lodash.pad": "^4.1.0",
        "lodash.padend": "^4.1.0",
        "lodash.padstart": "^4.1.0"
      }
    },
    "get-caller-file": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/get-caller-file/-/get-caller-file-1.0.3.tgz",
      "integrity": "sha512-3t6rVToeoZfYSGd8YoLFR2DJkiQrIiUrGcjvFX2mDw3bn6k2OtwHN0TNCLbBO+w8qTvimhDkv+LSscbJY1vE6w=="
    },
    "get-stream": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/get-stream/-/get-stream-3.0.0.tgz",
      "integrity": "sha1-jpQ9E1jcN1VQVOy+LtsFqhdO3hQ="
    },
    "get-value": {
      "version": "2.0.6",
      "resolved": "https://registry.npmjs.org/get-value/-/get-value-2.0.6.tgz",
      "integrity": "sha1-3BXKHGcjh8p2vTesCjlbogQqLCg="
    },
    "glob": {
      "version": "7.1.3",
      "resolved": "https://registry.npmjs.org/glob/-/glob-7.1.3.tgz",
      "integrity": "sha512-vcfuiIxogLV4DlGBHIUOwI0IbrJ8HWPc4MU7HzviGeNho/UJDfi6B5p3sHeWIQ0KGIU0Jpxi5ZHxemQfLkkAwQ==",
      "requires": {
        "fs.realpath": "^1.0.0",
        "inflight": "^1.0.4",
        "inherits": "2",
        "minimatch": "^3.0.4",
        "once": "^1.3.0",
        "path-is-absolute": "^1.0.0"
      }
    },
    "glob-base": {
      "version": "0.3.0",
      "resolved": "https://registry.npmjs.org/glob-base/-/glob-base-0.3.0.tgz",
      "integrity": "sha1-27Fk9iIbHAscz4Kuoyi0l98Oo8Q=",
      "requires": {
        "glob-parent": "^2.0.0",
        "is-glob": "^2.0.0"
      }
    },
    "glob-parent": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/glob-parent/-/glob-parent-2.0.0.tgz",
      "integrity": "sha1-gTg9ctsFT8zPUzbaqQLxgvbtuyg=",
      "requires": {
        "is-glob": "^2.0.0"
      }
    },
    "global": {
      "version": "4.3.2",
      "resolved": "https://registry.npmjs.org/global/-/global-4.3.2.tgz",
      "integrity": "sha1-52mJJopsdMOJCLEwWxD8DjlOnQ8=",
      "requires": {
        "min-document": "^2.19.0",
        "process": "~0.5.1"
      }
    },
    "globals": {
      "version": "11.11.0",
      "resolved": "https://registry.npmjs.org/globals/-/globals-11.11.0.tgz",
      "integrity": "sha512-WHq43gS+6ufNOEqlrDBxVEbb8ntfXrfAUU2ZOpCxrBdGKW3gyv8mCxAfIBD0DroPKGrJ2eSsXsLtY9MPntsyTw=="
    },
    "graceful-fs": {
      "version": "4.1.15",
      "resolved": "https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.15.tgz",
      "integrity": "sha512-6uHUhOPEBgQ24HM+r6b/QwWfZq+yiFcipKFrOFiBEnWdy5sdzYoi+pJeQaPI5qOLRFqWmAXUPQNsielzdLoecA=="
    },
    "graphql": {
      "version": "14.1.1",
      "resolved": "https://registry.npmjs.org/graphql/-/graphql-14.1.1.tgz",
      "integrity": "sha512-C5zDzLqvfPAgTtP8AUPIt9keDabrdRAqSWjj2OPRKrKxI9Fb65I36s1uCs1UUBFnSWTdO7hyHi7z1ZbwKMKF6Q==",
      "requires": {
        "iterall": "^1.2.2"
      }
    },
    "graphql-tag": {
      "version": "2.10.1",
      "resolved": "https://registry.npmjs.org/graphql-tag/-/graphql-tag-2.10.1.tgz",
      "integrity": "sha512-jApXqWBzNXQ8jYa/HLkZJaVw9jgwNqZkywa2zfFn16Iv1Zb7ELNHkJaXHR7Quvd5SIGsy6Ny7SUKATgnu05uEg=="
    },
    "growly": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/growly/-/growly-1.3.0.tgz",
      "integrity": "sha1-8QdIy+dq+WS3yWyTxrzCivEgwIE="
    },
    "gud": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/gud/-/gud-1.0.0.tgz",
      "integrity": "sha512-zGEOVKFM5sVPPrYs7J5/hYEw2Pof8KCyOwyhG8sAF26mCAeUFAcYPu1mwB7hhpIP29zOIBaDqwuHdLp0jvZXjw=="
    },
    "has-ansi": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/has-ansi/-/has-ansi-2.0.0.tgz",
      "integrity": "sha1-NPUEnOHs3ysGSa8+8k5F7TVBbZE=",
      "requires": {
        "ansi-regex": "^2.0.0"
      }
    },
    "has-flag": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-3.0.0.tgz",
      "integrity": "sha1-tdRU3CGZriJWmfNGfloH87lVuv0="
    },
    "has-unicode": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/has-unicode/-/has-unicode-2.0.1.tgz",
      "integrity": "sha1-4Ob+aijPUROIVeCG0Wkedx3iqLk="
    },
    "has-value": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/has-value/-/has-value-1.0.0.tgz",
      "integrity": "sha1-GLKB2lhbHFxR3vJMkw7SmgvmsXc=",
      "requires": {
        "get-value": "^2.0.6",
        "has-values": "^1.0.0",
        "isobject": "^3.0.0"
      },
      "dependencies": {
        "isobject": {
          "version": "3.0.1",
          "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
          "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8="
        }
      }
    },
    "has-values": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/has-values/-/has-values-1.0.0.tgz",
      "integrity": "sha1-lbC2P+whRmGab+V/51Yo1aOe/k8=",
      "requires": {
        "is-number": "^3.0.0",
        "kind-of": "^4.0.0"
      },
      "dependencies": {
        "is-number": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/is-number/-/is-number-3.0.0.tgz",
          "integrity": "sha1-JP1iAaR4LPUFYcgQJ2r8fRLXEZU=",
          "requires": {
            "kind-of": "^3.0.2"
          },
          "dependencies": {
            "kind-of": {
              "version": "3.2.2",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
              "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
              "requires": {
                "is-buffer": "^1.1.5"
              }
            }
          }
        },
        "kind-of": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-4.0.0.tgz",
          "integrity": "sha1-IIE989cSkosgc3hpGkUGb65y3Vc=",
          "requires": {
            "is-buffer": "^1.1.5"
          }
        }
      }
    },
    "hoist-non-react-statics": {
      "version": "2.5.5",
      "resolved": "https://registry.npmjs.org/hoist-non-react-statics/-/hoist-non-react-statics-2.5.5.tgz",
      "integrity": "sha512-rqcy4pJo55FTTLWt+bU8ukscqHeE/e9KWvsOW2b/a3afxQZhwkQdT1rPPCJ0rYXdj4vNcasY8zHTH+jF/qStxw=="
    },
    "home-or-tmp": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/home-or-tmp/-/home-or-tmp-2.0.0.tgz",
      "integrity": "sha1-42w/LSyufXRqhX440Y1fMqeILbg=",
      "requires": {
        "os-homedir": "^1.0.0",
        "os-tmpdir": "^1.0.1"
      }
    },
    "hosted-git-info": {
      "version": "2.7.1",
      "resolved": "https://registry.npmjs.org/hosted-git-info/-/hosted-git-info-2.7.1.tgz",
      "integrity": "sha512-7T/BxH19zbcCTa8XkMlbK5lTo1WtgkFi3GvdWEyNuc4Vex7/9Dqbnpsf4JMydcfj9HCg4zUWFTL3Za6lapg5/w=="
    },
    "http-errors": {
      "version": "1.6.3",
      "resolved": "https://registry.npmjs.org/http-errors/-/http-errors-1.6.3.tgz",
      "integrity": "sha1-i1VoC7S+KDoLW/TqLjhYC+HZMg0=",
      "requires": {
        "depd": "~1.1.2",
        "inherits": "2.0.3",
        "setprototypeof": "1.1.0",
        "statuses": ">= 1.4.0 < 2"
      },
      "dependencies": {
        "statuses": {
          "version": "1.5.0",
          "resolved": "https://registry.npmjs.org/statuses/-/statuses-1.5.0.tgz",
          "integrity": "sha1-Fhx9rBd2Wf2YEfQ3cfqZOBR4Yow="
        }
      }
    },
    "iconv-lite": {
      "version": "0.4.24",
      "resolved": "https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.24.tgz",
      "integrity": "sha512-v3MXnZAcvnywkTUEZomIActle7RXXeedOR31wwl7VlyoXO4Qi9arvSenNQWne1TcRwhCL1HwLI21bEqdpj8/rA==",
      "requires": {
        "safer-buffer": ">= 2.1.2 < 3"
      }
    },
    "image-size": {
      "version": "0.6.3",
      "resolved": "https://registry.npmjs.org/image-size/-/image-size-0.6.3.tgz",
      "integrity": "sha512-47xSUiQioGaB96nqtp5/q55m0aBQSQdyIloMOc/x+QVTDZLNmXE892IIDrJ0hM1A5vcNUDD5tDffkSP5lCaIIA=="
    },
    "immediate": {
      "version": "3.2.3",
      "resolved": "https://registry.npmjs.org/immediate/-/immediate-3.2.3.tgz",
      "integrity": "sha1-0UD6j2FGWb1lQSMwl92qwlzdmRw="
    },
    "immutable-tuple": {
      "version": "0.4.10",
      "resolved": "https://registry.npmjs.org/immutable-tuple/-/immutable-tuple-0.4.10.tgz",
      "integrity": "sha512-45jheDbc3Kr5Cw8EtDD+4woGRUV0utIrJBZT8XH0TPZRfm8tzT0/sLGGzyyCCFqFMG5Pv5Igf3WY/arn6+8V9Q=="
    },
    "import-fresh": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/import-fresh/-/import-fresh-2.0.0.tgz",
      "integrity": "sha1-2BNVwVYS04bGH53dOSLUMEgipUY=",
      "requires": {
        "caller-path": "^2.0.0",
        "resolve-from": "^3.0.0"
      }
    },
    "imurmurhash": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/imurmurhash/-/imurmurhash-0.1.4.tgz",
      "integrity": "sha1-khi5srkoojixPcT7a21XbyMUU+o="
    },
    "inflight": {
      "version": "1.0.6",
      "resolved": "https://registry.npmjs.org/inflight/-/inflight-1.0.6.tgz",
      "integrity": "sha1-Sb1jMdfQLQwJvJEKEHW6gWW1bfk=",
      "requires": {
        "once": "^1.3.0",
        "wrappy": "1"
      }
    },
    "inherits": {
      "version": "2.0.3",
      "resolved": "https://registry.npmjs.org/inherits/-/inherits-2.0.3.tgz",
      "integrity": "sha1-Yzwsg+PaQqUC9SRmAiSA9CCCYd4="
    },
    "inquirer": {
      "version": "3.3.0",
      "resolved": "https://registry.npmjs.org/inquirer/-/inquirer-3.3.0.tgz",
      "integrity": "sha512-h+xtnyk4EwKvFWHrUYsWErEVR+igKtLdchu+o0Z1RL7VU/jVMFbYir2bp6bAj8efFNxWqHX0dIss6fJQ+/+qeQ==",
      "requires": {
        "ansi-escapes": "^3.0.0",
        "chalk": "^2.0.0",
        "cli-cursor": "^2.1.0",
        "cli-width": "^2.0.0",
        "external-editor": "^2.0.4",
        "figures": "^2.0.0",
        "lodash": "^4.3.0",
        "mute-stream": "0.0.7",
        "run-async": "^2.2.0",
        "rx-lite": "^4.0.8",
        "rx-lite-aggregates": "^4.0.8",
        "string-width": "^2.1.0",
        "strip-ansi": "^4.0.0",
        "through": "^2.3.6"
      },
      "dependencies": {
        "ansi-regex": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-3.0.0.tgz",
          "integrity": "sha1-7QMXwyIGT3lGbAKWa922Bas32Zg="
        },
        "chalk": {
          "version": "2.4.2",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-2.4.2.tgz",
          "integrity": "sha512-Mti+f9lpJNcwF4tWV8/OrTTtF1gZi+f8FqlyAdouralcFWFQWF2+NgCHShjkCb+IFBLq9buZwE1xckQU4peSuQ==",
          "requires": {
            "ansi-styles": "^3.2.1",
            "escape-string-regexp": "^1.0.5",
            "supports-color": "^5.3.0"
          }
        },
        "strip-ansi": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-4.0.0.tgz",
          "integrity": "sha1-qEeQIusaw2iocTibY1JixQXuNo8=",
          "requires": {
            "ansi-regex": "^3.0.0"
          }
        },
        "supports-color": {
          "version": "5.5.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-5.5.0.tgz",
          "integrity": "sha512-QjVjwdXIt408MIiAqCX4oUKsgU2EqAGzs2Ppkm4aQYbjm+ZEWEcW4SfFNTr4uMNZma0ey4f5lgLrkB0aX0QMow==",
          "requires": {
            "has-flag": "^3.0.0"
          }
        }
      }
    },
    "invariant": {
      "version": "2.2.4",
      "resolved": "https://registry.npmjs.org/invariant/-/invariant-2.2.4.tgz",
      "integrity": "sha512-phJfQVBuaJM5raOpJjSfkiD6BpbCE4Ns//LaXl6wGYtUBY83nWS6Rf9tXm2e8VaK60JEjYldbPif/A2B1C2gNA==",
      "requires": {
        "loose-envify": "^1.0.0"
      }
    },
    "invert-kv": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/invert-kv/-/invert-kv-1.0.0.tgz",
      "integrity": "sha1-EEqOSqym09jNFXqO+L+rLXo//bY="
    },
    "is-accessor-descriptor": {
      "version": "0.1.6",
      "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-0.1.6.tgz",
      "integrity": "sha1-qeEss66Nh2cn7u84Q/igiXtcmNY=",
      "requires": {
        "kind-of": "^3.0.2"
      },
      "dependencies": {
        "kind-of": {
          "version": "3.2.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
          "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
          "requires": {
            "is-buffer": "^1.1.5"
          }
        }
      }
    },
    "is-arrayish": {
      "version": "0.3.2",
      "resolved": "https://registry.npmjs.org/is-arrayish/-/is-arrayish-0.3.2.tgz",
      "integrity": "sha512-eVRqCvVlZbuw3GrM63ovNSNAeA1K16kaR/LRY/92w0zxQ5/1YzwblUX652i4Xs9RwAGjW9d9y6X88t8OaAJfWQ=="
    },
    "is-buffer": {
      "version": "1.1.6",
      "resolved": "https://registry.npmjs.org/is-buffer/-/is-buffer-1.1.6.tgz",
      "integrity": "sha512-NcdALwpXkTm5Zvvbk7owOUSvVvBKDgKP5/ewfXEznmQFfs4ZRmanOeKBTjRVjka3QFoN6XJ+9F3USqfHqTaU5w=="
    },
    "is-data-descriptor": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-0.1.4.tgz",
      "integrity": "sha1-C17mSDiOLIYCgueT8YVv7D8wG1Y=",
      "requires": {
        "kind-of": "^3.0.2"
      },
      "dependencies": {
        "kind-of": {
          "version": "3.2.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
          "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
          "requires": {
            "is-buffer": "^1.1.5"
          }
        }
      }
    },
    "is-descriptor": {
      "version": "0.1.6",
      "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-0.1.6.tgz",
      "integrity": "sha512-avDYr0SB3DwO9zsMov0gKCESFYqCnE4hq/4z3TdUlukEy5t9C0YRq7HLrsN52NAcqXKaepeCD0n+B0arnVG3Hg==",
      "requires": {
        "is-accessor-descriptor": "^0.1.6",
        "is-data-descriptor": "^0.1.4",
        "kind-of": "^5.0.0"
      },
      "dependencies": {
        "kind-of": {
          "version": "5.1.0",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-5.1.0.tgz",
          "integrity": "sha512-NGEErnH6F2vUuXDh+OlbcKW7/wOcfdRHaZ7VWtqCztfHri/++YKmP51OdWeGPuqCOba6kk2OTe5d02VmTB80Pw=="
        }
      }
    },
    "is-directory": {
      "version": "0.3.1",
      "resolved": "https://registry.npmjs.org/is-directory/-/is-directory-0.3.1.tgz",
      "integrity": "sha1-YTObbyR1/Hcv2cnYP1yFddwVSuE="
    },
    "is-dotfile": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/is-dotfile/-/is-dotfile-1.0.3.tgz",
      "integrity": "sha1-pqLzL/0t+wT1yiXs0Pa4PPeYoeE="
    },
    "is-equal-shallow": {
      "version": "0.1.3",
      "resolved": "https://registry.npmjs.org/is-equal-shallow/-/is-equal-shallow-0.1.3.tgz",
      "integrity": "sha1-IjgJj8Ih3gvPpdnqxMRdY4qhxTQ=",
      "requires": {
        "is-primitive": "^2.0.0"
      }
    },
    "is-extendable": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-0.1.1.tgz",
      "integrity": "sha1-YrEQ4omkcUGOPsNqYX1HLjAd/Ik="
    },
    "is-extglob": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/is-extglob/-/is-extglob-1.0.0.tgz",
      "integrity": "sha1-rEaBd8SUNAWgkvyPKXYMb/xiBsA="
    },
    "is-finite": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/is-finite/-/is-finite-1.0.2.tgz",
      "integrity": "sha1-zGZ3aVYCvlUO8R6LSqYwU0K20Ko=",
      "requires": {
        "number-is-nan": "^1.0.0"
      }
    },
    "is-fullwidth-code-point": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/is-fullwidth-code-point/-/is-fullwidth-code-point-1.0.0.tgz",
      "integrity": "sha1-754xOG8DGn8NZDr4L95QxFfvAMs=",
      "requires": {
        "number-is-nan": "^1.0.0"
      }
    },
    "is-glob": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/is-glob/-/is-glob-2.0.1.tgz",
      "integrity": "sha1-0Jb5JqPe1WAPP9/ZEZjLCIjC2GM=",
      "requires": {
        "is-extglob": "^1.0.0"
      }
    },
    "is-number": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/is-number/-/is-number-2.1.0.tgz",
      "integrity": "sha1-Afy7s5NGOlSPL0ZszhbezknbkI8=",
      "requires": {
        "kind-of": "^3.0.2"
      },
      "dependencies": {
        "kind-of": {
          "version": "3.2.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
          "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
          "requires": {
            "is-buffer": "^1.1.5"
          }
        }
      }
    },
    "is-plain-object": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/is-plain-object/-/is-plain-object-2.0.4.tgz",
      "integrity": "sha512-h5PpgXkWitc38BBMYawTYMWJHFZJVnBquFE57xFpjB8pJFiF6gZ+bU+WyI/yqXiFR5mdLsgYNaPe8uao6Uv9Og==",
      "requires": {
        "isobject": "^3.0.1"
      },
      "dependencies": {
        "isobject": {
          "version": "3.0.1",
          "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
          "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8="
        }
      }
    },
    "is-posix-bracket": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/is-posix-bracket/-/is-posix-bracket-0.1.1.tgz",
      "integrity": "sha1-MzTceXdDaOkvAW5vvAqI9c1ua8Q="
    },
    "is-primitive": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/is-primitive/-/is-primitive-2.0.0.tgz",
      "integrity": "sha1-IHurkWOEmcB7Kt8kCkGochADRXU="
    },
    "is-promise": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/is-promise/-/is-promise-2.1.0.tgz",
      "integrity": "sha1-eaKp7OfwlugPNtKy87wWwf9L8/o="
    },
    "is-stream": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/is-stream/-/is-stream-1.1.0.tgz",
      "integrity": "sha1-EtSj3U5o4Lec6428hBc66A2RykQ="
    },
    "is-windows": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/is-windows/-/is-windows-1.0.2.tgz",
      "integrity": "sha512-eXK1UInq2bPmjyX6e3VHIzMLobc4J94i4AWn+Hpq3OU5KkrRC96OAcR3PRJ/pGu6m8TRnBHP9dkXQVsT/COVIA=="
    },
    "is-wsl": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/is-wsl/-/is-wsl-1.1.0.tgz",
      "integrity": "sha1-HxbkqiKwTRM2tmGIpmrzxgDDpm0="
    },
    "isarray": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/isarray/-/isarray-1.0.0.tgz",
      "integrity": "sha1-u5NdSFgsuhaMBoNJV6VKPgcSTxE="
    },
    "isexe": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/isexe/-/isexe-2.0.0.tgz",
      "integrity": "sha1-6PvzdNxVb/iUehDcsFctYz8s+hA="
    },
    "isobject": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/isobject/-/isobject-2.1.0.tgz",
      "integrity": "sha1-8GVWEJaj8dou9GJy+BXIQNh+DIk=",
      "requires": {
        "isarray": "1.0.0"
      }
    },
    "isomorphic-fetch": {
      "version": "2.2.1",
      "resolved": "https://registry.npmjs.org/isomorphic-fetch/-/isomorphic-fetch-2.2.1.tgz",
      "integrity": "sha1-YRrhrPFPXoH3KVB0coGf6XM1WKk=",
      "requires": {
        "node-fetch": "^1.0.1",
        "whatwg-fetch": ">=0.10.0"
      },
      "dependencies": {
        "node-fetch": {
          "version": "1.7.3",
          "resolved": "https://registry.npmjs.org/node-fetch/-/node-fetch-1.7.3.tgz",
          "integrity": "sha512-NhZ4CsKx7cYm2vSrBAr2PvFOe6sWDf0UYLRqA6svUYg7+/TSfVAu49jYC4BvQ4Sms9SZgdqGBgroqfDhJdTyKQ==",
          "requires": {
            "encoding": "^0.1.11",
            "is-stream": "^1.0.1"
          }
        }
      }
    },
    "iterall": {
      "version": "1.2.2",
      "resolved": "https://registry.npmjs.org/iterall/-/iterall-1.2.2.tgz",
      "integrity": "sha512-yynBb1g+RFUPY64fTrFv7nsjRrENBQJaX2UL+2Szc9REFrSNm1rpSXHGzhmAy7a9uv3vlvgBlXnf9RqmPH1/DA=="
    },
    "jest-docblock": {
      "version": "23.2.0",
      "resolved": "https://registry.npmjs.org/jest-docblock/-/jest-docblock-23.2.0.tgz",
      "integrity": "sha1-8IXh8YVI2Z/dabICB+b9VdkTg6c=",
      "requires": {
        "detect-newline": "^2.1.0"
      }
    },
    "jest-haste-map": {
      "version": "23.5.0",
      "resolved": "https://registry.npmjs.org/jest-haste-map/-/jest-haste-map-23.5.0.tgz",
      "integrity": "sha512-bt9Swigb6KZ6ZQq/fQDUwdUeHenVvZ6G/lKwJjwRGp+Fap8D4B3bND3FaeJg7vXVsLX8hXshRArbVxLop/5wLw==",
      "requires": {
        "fb-watchman": "^2.0.0",
        "graceful-fs": "^4.1.11",
        "invariant": "^2.2.4",
        "jest-docblock": "^23.2.0",
        "jest-serializer": "^23.0.1",
        "jest-worker": "^23.2.0",
        "micromatch": "^2.3.11",
        "sane": "^2.0.0"
      }
    },
    "jest-react-native": {
      "version": "18.0.0",
      "resolved": "https://registry.npmjs.org/jest-react-native/-/jest-react-native-18.0.0.tgz",
      "integrity": "sha1-d92QnwaTJFmfInxYxhwuYhaHJro="
    },
    "jest-serializer": {
      "version": "23.0.1",
      "resolved": "https://registry.npmjs.org/jest-serializer/-/jest-serializer-23.0.1.tgz",
      "integrity": "sha1-o3dq6zEekP6D+rnlM+hRAr0WQWU="
    },
    "jest-worker": {
      "version": "23.2.0",
      "resolved": "https://registry.npmjs.org/jest-worker/-/jest-worker-23.2.0.tgz",
      "integrity": "sha1-+vcGqNo2+uYOsmlXJX+ntdjqArk=",
      "requires": {
        "merge-stream": "^1.0.1"
      }
    },
    "js-tokens": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/js-tokens/-/js-tokens-4.0.0.tgz",
      "integrity": "sha512-RdJUflcE3cUzKiMqQgsCu06FPu9UdIJO0beYbPhHN4k6apgJtifcoCtT9bcxOpYBtpD2kCM6Sbzg4CausW/PKQ=="
    },
    "js-yaml": {
      "version": "3.12.1",
      "resolved": "https://registry.npmjs.org/js-yaml/-/js-yaml-3.12.1.tgz",
      "integrity": "sha512-um46hB9wNOKlwkHgiuyEVAybXBjwFUV0Z/RaHJblRd9DXltue9FTYvzCr9ErQrK9Adz5MU4gHWVaNUfdmrC8qA==",
      "requires": {
        "argparse": "^1.0.7",
        "esprima": "^4.0.0"
      }
    },
    "jsesc": {
      "version": "2.5.2",
      "resolved": "https://registry.npmjs.org/jsesc/-/jsesc-2.5.2.tgz",
      "integrity": "sha512-OYu7XEzjkCQ3C5Ps3QIZsQfNpqoJyZZA99wd9aWd05NCtC5pWOkShK2mkL6HXQR6/Cy2lbNdPlZBpuQHXE63gA=="
    },
    "json-parse-better-errors": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/json-parse-better-errors/-/json-parse-better-errors-1.0.2.tgz",
      "integrity": "sha512-mrqyZKfX5EhL7hvqcV6WG1yYjnjeuYDzDhhcAAUrq8Po85NBQBJP+ZDUT75qZQ98IkUoBqdkExkukOU7Ts2wrw=="
    },
    "json-schema-traverse": {
      "version": "0.4.1",
      "resolved": "https://registry.npmjs.org/json-schema-traverse/-/json-schema-traverse-0.4.1.tgz",
      "integrity": "sha512-xbbCH5dCYU5T8LcEhhuh7HJ88HXuW3qsI3Y0zOZFKfZEHcpWiHU/Jxzk629Brsab/mMiHQti9wMP+845RPe3Vg=="
    },
    "json-stable-stringify": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/json-stable-stringify/-/json-stable-stringify-1.0.1.tgz",
      "integrity": "sha1-mnWdOcXy/1A/1TAGRu1EX4jE+a8=",
      "requires": {
        "jsonify": "~0.0.0"
      }
    },
    "json5": {
      "version": "0.5.1",
      "resolved": "https://registry.npmjs.org/json5/-/json5-0.5.1.tgz",
      "integrity": "sha1-Hq3nrMASA0rYTiOWdn6tn6VJWCE="
    },
    "jsonfile": {
      "version": "2.4.0",
      "resolved": "https://registry.npmjs.org/jsonfile/-/jsonfile-2.4.0.tgz",
      "integrity": "sha1-NzaitCi4e72gzIO1P6PWM6NcKug=",
      "requires": {
        "graceful-fs": "^4.1.6"
      }
    },
    "jsonify": {
      "version": "0.0.0",
      "resolved": "https://registry.npmjs.org/jsonify/-/jsonify-0.0.0.tgz",
      "integrity": "sha1-LHS27kHZPKUbe1qu6PUDYx0lKnM="
    },
    "kind-of": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-1.1.0.tgz",
      "integrity": "sha1-FAo9LUGjbS78+pN3tiwk+ElaXEQ="
    },
    "klaw": {
      "version": "1.3.1",
      "resolved": "https://registry.npmjs.org/klaw/-/klaw-1.3.1.tgz",
      "integrity": "sha1-QIhDO0azsbolnXh4XY6W9zugJDk=",
      "requires": {
        "graceful-fs": "^4.1.9"
      }
    },
    "lcid": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/lcid/-/lcid-1.0.0.tgz",
      "integrity": "sha1-MIrMr6C8SDo4Z7S28rlQYlHRuDU=",
      "requires": {
        "invert-kv": "^1.0.0"
      }
    },
    "load-json-file": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/load-json-file/-/load-json-file-2.0.0.tgz",
      "integrity": "sha1-eUfkIUmvgNaWy/eXvKq8/h/inKg=",
      "requires": {
        "graceful-fs": "^4.1.2",
        "parse-json": "^2.2.0",
        "pify": "^2.0.0",
        "strip-bom": "^3.0.0"
      }
    },
    "loader-utils": {
      "version": "1.2.3",
      "resolved": "https://registry.npmjs.org/loader-utils/-/loader-utils-1.2.3.tgz",
      "integrity": "sha512-fkpz8ejdnEMG3s37wGL07iSBDg99O9D5yflE9RGNH3hRdx9SOwYfnGYdZOUIZitN8E+E2vkq3MUMYMvPYl5ZZA==",
      "requires": {
        "big.js": "^5.2.2",
        "emojis-list": "^2.0.0",
        "json5": "^1.0.1"
      },
      "dependencies": {
        "json5": {
          "version": "1.0.1",
          "resolved": "https://registry.npmjs.org/json5/-/json5-1.0.1.tgz",
          "integrity": "sha512-aKS4WQjPenRxiQsC93MNfjx+nbF4PAdYzmd/1JIj8HYzqfbu86beTuNgXDzPknWk0n0uARlyewZo4s++ES36Ow==",
          "requires": {
            "minimist": "^1.2.0"
          }
        },
        "minimist": {
          "version": "1.2.0",
          "resolved": "https://registry.npmjs.org/minimist/-/minimist-1.2.0.tgz",
          "integrity": "sha1-o1AIsg9BOD7sH7kU9M1d95omQoQ="
        }
      }
    },
    "locate-path": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/locate-path/-/locate-path-2.0.0.tgz",
      "integrity": "sha1-K1aLJl7slExtnA3pw9u7ygNUzY4=",
      "requires": {
        "p-locate": "^2.0.0",
        "path-exists": "^3.0.0"
      }
    },
    "lodash": {
      "version": "4.17.11",
      "resolved": "https://registry.npmjs.org/lodash/-/lodash-4.17.11.tgz",
      "integrity": "sha512-cQKh8igo5QUhZ7lg38DYWAxMvjSAKG0A8wGSVimP07SIUEK2UO+arSRKbRZWtelMtN5V0Hkwh5ryOto/SshYIg=="
    },
    "lodash-es": {
      "version": "4.17.11",
      "resolved": "https://registry.npmjs.org/lodash-es/-/lodash-es-4.17.11.tgz",
      "integrity": "sha512-DHb1ub+rMjjrxqlB3H56/6MXtm1lSksDp2rA2cNWjG8mlDUYFhUj3Di2Zn5IwSU87xLv8tNIQ7sSwE/YOX/D/Q=="
    },
    "lodash.filter": {
      "version": "4.6.0",
      "resolved": "https://registry.npmjs.org/lodash.filter/-/lodash.filter-4.6.0.tgz",
      "integrity": "sha1-ZosdSYFgOuHMWm+nYBQ+SAtMSs4="
    },
    "lodash.get": {
      "version": "4.4.2",
      "resolved": "https://registry.npmjs.org/lodash.get/-/lodash.get-4.4.2.tgz",
      "integrity": "sha1-LRd/ZS+jHpObRDjVNBSZ36OCXpk="
    },
    "lodash.isequal": {
      "version": "4.5.0",
      "resolved": "https://registry.npmjs.org/lodash.isequal/-/lodash.isequal-4.5.0.tgz",
      "integrity": "sha1-QVxEePK8wwEgwizhDtMib30+GOA="
    },
    "lodash.isfunction": {
      "version": "3.0.9",
      "resolved": "https://registry.npmjs.org/lodash.isfunction/-/lodash.isfunction-3.0.9.tgz",
      "integrity": "sha512-AirXNj15uRIMMPihnkInB4i3NHeb4iBtNg9WRWuK2o31S+ePwwNmDPaTL3o7dTJ+VXNZim7rFs4rxN4YU1oUJw=="
    },
    "lodash.isobject": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/lodash.isobject/-/lodash.isobject-3.0.2.tgz",
      "integrity": "sha1-PI+41bW/S/kK4G4U8qUwpO2TXh0="
    },
    "lodash.map": {
      "version": "4.6.0",
      "resolved": "https://registry.npmjs.org/lodash.map/-/lodash.map-4.6.0.tgz",
      "integrity": "sha1-dx7Hg540c9nEzeKLGTlMNWL09tM="
    },
    "lodash.mapvalues": {
      "version": "4.6.0",
      "resolved": "https://registry.npmjs.org/lodash.mapvalues/-/lodash.mapvalues-4.6.0.tgz",
      "integrity": "sha1-G6+lAF3p3W9PJmaMMMo3IwzJaJw="
    },
    "lodash.merge": {
      "version": "4.6.1",
      "resolved": "https://registry.npmjs.org/lodash.merge/-/lodash.merge-4.6.1.tgz",
      "integrity": "sha512-AOYza4+Hf5z1/0Hztxpm2/xiPZgi/cjMqdnKTUWTBSKchJlxXXuUSxCCl8rJlf4g6yww/j6mA8nC8Hw/EZWxKQ=="
    },
    "lodash.omit": {
      "version": "4.5.0",
      "resolved": "https://registry.npmjs.org/lodash.omit/-/lodash.omit-4.5.0.tgz",
      "integrity": "sha1-brGa5aHuHdnfC5aeZs4Lf6MLXmA="
    },
    "lodash.pad": {
      "version": "4.5.1",
      "resolved": "https://registry.npmjs.org/lodash.pad/-/lodash.pad-4.5.1.tgz",
      "integrity": "sha1-QzCUmoM6fI2iLMIPaibE1Z3runA="
    },
    "lodash.padend": {
      "version": "4.6.1",
      "resolved": "https://registry.npmjs.org/lodash.padend/-/lodash.padend-4.6.1.tgz",
      "integrity": "sha1-U8y6BH0G4VjTEfRdpiX05J5vFm4="
    },
    "lodash.padstart": {
      "version": "4.6.1",
      "resolved": "https://registry.npmjs.org/lodash.padstart/-/lodash.padstart-4.6.1.tgz",
      "integrity": "sha1-0uPuv/DZ05rVD1y9G1KnvOa7YRs="
    },
    "lodash.pick": {
      "version": "4.4.0",
      "resolved": "https://registry.npmjs.org/lodash.pick/-/lodash.pick-4.4.0.tgz",
      "integrity": "sha1-UvBWEP/53tQiYRRB7R/BI6AwAbM="
    },
    "lodash.throttle": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/lodash.throttle/-/lodash.throttle-4.1.1.tgz",
      "integrity": "sha1-wj6RtxAkKscMN/HhzaknTMOb8vQ="
    },
    "lodash.tonumber": {
      "version": "4.0.3",
      "resolved": "https://registry.npmjs.org/lodash.tonumber/-/lodash.tonumber-4.0.3.tgz",
      "integrity": "sha1-C5azGzVnJ5Prf1pj7nkfG56QJdk="
    },
    "lodash.zipobject": {
      "version": "4.1.3",
      "resolved": "https://registry.npmjs.org/lodash.zipobject/-/lodash.zipobject-4.1.3.tgz",
      "integrity": "sha1-s5n1q6j/YqdG9peb8gshT5ZNvvg="
    },
    "loose-envify": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/loose-envify/-/loose-envify-1.4.0.tgz",
      "integrity": "sha512-lyuxPGr/Wfhrlem2CL/UcnUc1zcqKAImBDzukY7Y5F/yQiNdko6+fRLevlw1HgMySw7f611UIY408EtxRSoK3Q==",
      "requires": {
        "js-tokens": "^3.0.0 || ^4.0.0"
      }
    },
    "lottie-ios": {
      "version": "2.5.0",
      "resolved": "https://registry.npmjs.org/lottie-ios/-/lottie-ios-2.5.0.tgz",
      "integrity": "sha1-VcgI54XUppM7DBCzlVMLFwmLBd4="
    },
    "lottie-react-native": {
      "version": "2.5.0",
      "resolved": "https://registry.npmjs.org/lottie-react-native/-/lottie-react-native-2.5.0.tgz",
      "integrity": "sha1-BxG4s0vsd0FVLCS3Hv09TKs0dXE=",
      "requires": {
        "invariant": "^2.2.2",
        "lottie-ios": "^2.5.0",
        "prop-types": "^15.5.10",
        "react-native-safe-module": "^1.1.0"
      }
    },
    "lru-cache": {
      "version": "4.1.5",
      "resolved": "https://registry.npmjs.org/lru-cache/-/lru-cache-4.1.5.tgz",
      "integrity": "sha512-sWZlbEP2OsHNkXrMl5GYk/jKk70MBng6UU4YI/qGDYbgf6YbP4EvmqISbXCoJiRKs+1bSpFHVgQxvJ17F2li5g==",
      "requires": {
        "pseudomap": "^1.0.2",
        "yallist": "^2.1.2"
      }
    },
    "make-dir": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/make-dir/-/make-dir-1.3.0.tgz",
      "integrity": "sha512-2w31R7SJtieJJnQtGc7RVL2StM2vGYVfqUOvUDxH6bC6aJTxPxTF0GnIgCyu7tjockiUWAYQRbxa7vKn34s5sQ==",
      "requires": {
        "pify": "^3.0.0"
      },
      "dependencies": {
        "pify": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/pify/-/pify-3.0.0.tgz",
          "integrity": "sha1-5aSs0sEB/fPZpNB/DbxNtJ3SgXY="
        }
      }
    },
    "makeerror": {
      "version": "1.0.11",
      "resolved": "https://registry.npmjs.org/makeerror/-/makeerror-1.0.11.tgz",
      "integrity": "sha1-4BpckQnyr3lmDk6LlYd5AYT1qWw=",
      "requires": {
        "tmpl": "1.0.x"
      }
    },
    "map-cache": {
      "version": "0.2.2",
      "resolved": "https://registry.npmjs.org/map-cache/-/map-cache-0.2.2.tgz",
      "integrity": "sha1-wyq9C9ZSXZsFFkW7TyasXcmKDb8="
    },
    "map-visit": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/map-visit/-/map-visit-1.0.0.tgz",
      "integrity": "sha1-7Nyo8TFE5mDxtb1B8S80edmN+48=",
      "requires": {
        "object-visit": "^1.0.0"
      }
    },
    "math-random": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/math-random/-/math-random-1.0.4.tgz",
      "integrity": "sha512-rUxjysqif/BZQH2yhd5Aaq7vXMSx9NdEsQcyA07uEzIvxgI7zIr33gGsh+RU0/XjmQpCW7RsVof1vlkvQVCK5A=="
    },
    "md5-file": {
      "version": "3.2.3",
      "resolved": "https://registry.npmjs.org/md5-file/-/md5-file-3.2.3.tgz",
      "integrity": "sha512-3Tkp1piAHaworfcCgH0jKbTvj1jWWFgbvh2cXaNCgHwyTCBxxvD1Y04rmfpvdPm1P4oXMOpm6+2H7sr7v9v8Fw==",
      "requires": {
        "buffer-alloc": "^1.1.0"
      }
    },
    "mem": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/mem/-/mem-1.1.0.tgz",
      "integrity": "sha1-Xt1StIXKHZAP5kiVUFOZoN+kX3Y=",
      "requires": {
        "mimic-fn": "^1.0.0"
      }
    },
    "merge": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/merge/-/merge-1.2.1.tgz",
      "integrity": "sha512-VjFo4P5Whtj4vsLzsYBu5ayHhoHJ0UqNm7ibvShmbmoz7tGi0vXaoJbGdB+GmDMLUdg8DpQXEIeVDAe8MaABvQ=="
    },
    "merge-stream": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/merge-stream/-/merge-stream-1.0.1.tgz",
      "integrity": "sha1-QEEgLVCKNCugAXQAjfDCUbjBNeE=",
      "requires": {
        "readable-stream": "^2.0.1"
      }
    },
    "metro": {
      "version": "0.45.6",
      "resolved": "https://registry.npmjs.org/metro/-/metro-0.45.6.tgz",
      "integrity": "sha512-+RinU6Qcea/zX9xxfrgmeFBwJ3tsdgLyBJm4tQOmusU4kE8YEE4LQ3IGG60qk3wzYloflMB/8ilIGG4Z/gz2Ew==",
      "requires": {
        "@babel/core": "^7.0.0",
        "@babel/generator": "^7.0.0",
        "@babel/parser": "^7.0.0",
        "@babel/plugin-external-helpers": "^7.0.0",
        "@babel/template": "^7.0.0",
        "@babel/traverse": "^7.0.0",
        "@babel/types": "^7.0.0",
        "absolute-path": "^0.0.0",
        "async": "^2.4.0",
        "babel-preset-fbjs": "2.3.0",
        "chalk": "^1.1.1",
        "concat-stream": "^1.6.0",
        "connect": "^3.6.5",
        "debug": "^2.2.0",
        "denodeify": "^1.2.1",
        "eventemitter3": "^3.0.0",
        "fbjs": "0.8.17",
        "fs-extra": "^1.0.0",
        "graceful-fs": "^4.1.3",
        "image-size": "^0.6.0",
        "jest-docblock": "23.2.0",
        "jest-haste-map": "23.5.0",
        "jest-worker": "23.2.0",
        "json-stable-stringify": "^1.0.1",
        "lodash.throttle": "^4.1.1",
        "merge-stream": "^1.0.1",
        "metro-cache": "0.45.6",
        "metro-config": "0.45.6",
        "metro-core": "0.45.6",
        "metro-minify-uglify": "0.45.6",
        "metro-react-native-babel-preset": "0.45.6",
        "metro-resolver": "0.45.6",
        "metro-source-map": "0.45.6",
        "mime-types": "2.1.11",
        "mkdirp": "^0.5.1",
        "node-fetch": "^2.2.0",
        "nullthrows": "^1.1.0",
        "react-transform-hmr": "^1.0.4",
        "resolve": "^1.5.0",
        "rimraf": "^2.5.4",
        "serialize-error": "^2.1.0",
        "source-map": "^0.5.6",
        "temp": "0.8.3",
        "throat": "^4.1.0",
        "wordwrap": "^1.0.0",
        "write-file-atomic": "^1.2.0",
        "ws": "^1.1.0",
        "xpipe": "^1.0.5",
        "yargs": "^9.0.0"
      },
      "dependencies": {
        "metro-babel7-plugin-react-transform": {
          "version": "0.45.6",
          "resolved": "https://registry.npmjs.org/metro-babel7-plugin-react-transform/-/metro-babel7-plugin-react-transform-0.45.6.tgz",
          "integrity": "sha512-NsVKqiBaF+Tm3FXzqiEExl9iJG+EimbpQP5h9ygxBE4AsYRc2S3X/YD/1ds3RTHMgfhinWVaus+DrG5OqK5mTA==",
          "requires": {
            "@babel/helper-module-imports": "^7.0.0"
          }
        },
        "metro-react-native-babel-preset": {
          "version": "0.45.6",
          "resolved": "https://registry.npmjs.org/metro-react-native-babel-preset/-/metro-react-native-babel-preset-0.45.6.tgz",
          "integrity": "sha512-qh+iXlV2tDfvHYbhh1meihxnzXXXB8nF1fi8z2HFxqYDkFBM48XewXO6mLz97PL8lmuTGvX/2dYVuFtriENw1w==",
          "requires": {
            "@babel/plugin-proposal-class-properties": "^7.0.0",
            "@babel/plugin-proposal-export-default-from": "^7.0.0",
            "@babel/plugin-proposal-nullish-coalescing-operator": "^7.0.0",
            "@babel/plugin-proposal-object-rest-spread": "^7.0.0",
            "@babel/plugin-proposal-optional-catch-binding": "^7.0.0",
            "@babel/plugin-proposal-optional-chaining": "^7.0.0",
            "@babel/plugin-syntax-dynamic-import": "^7.0.0",
            "@babel/plugin-syntax-export-default-from": "^7.0.0",
            "@babel/plugin-transform-arrow-functions": "^7.0.0",
            "@babel/plugin-transform-block-scoping": "^7.0.0",
            "@babel/plugin-transform-classes": "^7.0.0",
            "@babel/plugin-transform-computed-properties": "^7.0.0",
            "@babel/plugin-transform-destructuring": "^7.0.0",
            "@babel/plugin-transform-exponentiation-operator": "^7.0.0",
            "@babel/plugin-transform-flow-strip-types": "^7.0.0",
            "@babel/plugin-transform-for-of": "^7.0.0",
            "@babel/plugin-transform-function-name": "^7.0.0",
            "@babel/plugin-transform-literals": "^7.0.0",
            "@babel/plugin-transform-modules-commonjs": "^7.0.0",
            "@babel/plugin-transform-object-assign": "^7.0.0",
            "@babel/plugin-transform-parameters": "^7.0.0",
            "@babel/plugin-transform-react-display-name": "^7.0.0",
            "@babel/plugin-transform-react-jsx": "^7.0.0",
            "@babel/plugin-transform-react-jsx-source": "^7.0.0",
            "@babel/plugin-transform-regenerator": "^7.0.0",
            "@babel/plugin-transform-shorthand-properties": "^7.0.0",
            "@babel/plugin-transform-spread": "^7.0.0",
            "@babel/plugin-transform-sticky-regex": "^7.0.0",
            "@babel/plugin-transform-template-literals": "^7.0.0",
            "@babel/plugin-transform-typescript": "^7.0.0",
            "@babel/plugin-transform-unicode-regex": "^7.0.0",
            "@babel/template": "^7.0.0",
            "metro-babel7-plugin-react-transform": "0.45.6",
            "react-transform-hmr": "^1.0.4"
          }
        },
        "mime-db": {
          "version": "1.23.0",
          "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.23.0.tgz",
          "integrity": "sha1-oxtAcK2uon1zLqMzdApk0OyaZlk="
        },
        "mime-types": {
          "version": "2.1.11",
          "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.11.tgz",
          "integrity": "sha1-wlnEcb2oCKhdbNGTtDCl+uRHOzw=",
          "requires": {
            "mime-db": "~1.23.0"
          }
        }
      }
    },
    "metro-babel-register": {
      "version": "0.45.6",
      "resolved": "https://registry.npmjs.org/metro-babel-register/-/metro-babel-register-0.45.6.tgz",
      "integrity": "sha512-Io8JinYIzGcXiTaO7o0DGw8wFcAiITTb7mLh3lbuJd9PndbPOo+jhrHkTsNtXc9MRHiT4KbEheXJ/QoeLKJK/Q==",
      "requires": {
        "@babel/core": "^7.0.0",
        "@babel/plugin-proposal-class-properties": "^7.0.0",
        "@babel/plugin-proposal-nullish-coalescing-operator": "^7.0.0",
        "@babel/plugin-proposal-object-rest-spread": "^7.0.0",
        "@babel/plugin-proposal-optional-catch-binding": "^7.0.0",
        "@babel/plugin-proposal-optional-chaining": "^7.0.0",
        "@babel/plugin-transform-async-to-generator": "^7.0.0",
        "@babel/plugin-transform-flow-strip-types": "^7.0.0",
        "@babel/plugin-transform-modules-commonjs": "^7.0.0",
        "@babel/register": "^7.0.0",
        "core-js": "^2.2.2",
        "escape-string-regexp": "^1.0.5"
      }
    },
    "metro-babel7-plugin-react-transform": {
      "version": "0.49.2",
      "resolved": "https://registry.npmjs.org/metro-babel7-plugin-react-transform/-/metro-babel7-plugin-react-transform-0.49.2.tgz",
      "integrity": "sha512-LpJT8UvqF/tvVqEwiLUTMjRPhEGdI8e2dr3424XaRANba3j0nqmrbKdJQsPE8TrcqMWR4RHmfsXk0ti5QrEvJg==",
      "requires": {
        "@babel/helper-module-imports": "^7.0.0"
      }
    },
    "metro-cache": {
      "version": "0.45.6",
      "resolved": "https://registry.npmjs.org/metro-cache/-/metro-cache-0.45.6.tgz",
      "integrity": "sha512-v7q2pLsI7oABEjpwPJwTd7ufwKvpctVOddcffI/2hRhuJC/seLlqkRt7kv+Q/WfaR9X4KLcEoIjZmgNy4cw1ag==",
      "requires": {
        "jest-serializer": "23.0.1",
        "metro-core": "0.45.6",
        "mkdirp": "^0.5.1",
        "rimraf": "^2.5.4"
      }
    },
    "metro-config": {
      "version": "0.45.6",
      "resolved": "https://registry.npmjs.org/metro-config/-/metro-config-0.45.6.tgz",
      "integrity": "sha512-ZhVtkpXhOi+qWi7vdE3HGIhyyBT1wtIukQuxTMwLTUluv2/1DClo/uX9inmf++CmOhOpU7QpqrMzl6vf+AwnOg==",
      "requires": {
        "cosmiconfig": "^5.0.5",
        "metro": "0.45.6",
        "metro-cache": "0.45.6",
        "metro-core": "0.45.6"
      }
    },
    "metro-core": {
      "version": "0.45.6",
      "resolved": "https://registry.npmjs.org/metro-core/-/metro-core-0.45.6.tgz",
      "integrity": "sha512-M0YkGnkjStdCsSNYVW+aVlJ4WjwcqjIhQV+VzEnGZYdyo6cMi9MxUZ69iV2jIxd3LAeaQQaNe8OQtQp8dfIh/g==",
      "requires": {
        "jest-haste-map": "23.5.0",
        "lodash.throttle": "^4.1.1",
        "metro-resolver": "0.45.6",
        "wordwrap": "^1.0.0"
      }
    },
    "metro-memory-fs": {
      "version": "0.45.6",
      "resolved": "https://registry.npmjs.org/metro-memory-fs/-/metro-memory-fs-0.45.6.tgz",
      "integrity": "sha512-YAGoNQVTM/vl65jR/ztucAZJIk0ejD3INZT0LiISRULBt6Rxfiqa22v5GG0Enq+95vlgmt26g+auHM2nxTUInQ=="
    },
    "metro-minify-uglify": {
      "version": "0.45.6",
      "resolved": "https://registry.npmjs.org/metro-minify-uglify/-/metro-minify-uglify-0.45.6.tgz",
      "integrity": "sha512-l+lZ7Gg6CN9XddgmwAbo7zOLT2QB9a6VALXLzmvr6gB1mc6SBZwtAh+hARvdymtcr1CgbaWADZPAA+W3oQZH4g==",
      "requires": {
        "uglify-es": "^3.1.9"
      }
    },
    "metro-react-native-babel-preset": {
      "version": "0.49.2",
      "resolved": "https://registry.npmjs.org/metro-react-native-babel-preset/-/metro-react-native-babel-preset-0.49.2.tgz",
      "integrity": "sha512-N0+4ramShYCHSAVEPUNWIZuKZskWj8/RDSoinhadHpdpHORMbMxLkexSOVHLluB+XFQ+DENLEx5oVPYwOlENBA==",
      "requires": {
        "@babel/plugin-proposal-class-properties": "^7.0.0",
        "@babel/plugin-proposal-export-default-from": "^7.0.0",
        "@babel/plugin-proposal-nullish-coalescing-operator": "^7.0.0",
        "@babel/plugin-proposal-object-rest-spread": "^7.0.0",
        "@babel/plugin-proposal-optional-catch-binding": "^7.0.0",
        "@babel/plugin-proposal-optional-chaining": "^7.0.0",
        "@babel/plugin-syntax-dynamic-import": "^7.0.0",
        "@babel/plugin-syntax-export-default-from": "^7.0.0",
        "@babel/plugin-transform-arrow-functions": "^7.0.0",
        "@babel/plugin-transform-block-scoping": "^7.0.0",
        "@babel/plugin-transform-classes": "^7.0.0",
        "@babel/plugin-transform-computed-properties": "^7.0.0",
        "@babel/plugin-transform-destructuring": "^7.0.0",
        "@babel/plugin-transform-exponentiation-operator": "^7.0.0",
        "@babel/plugin-transform-flow-strip-types": "^7.0.0",
        "@babel/plugin-transform-for-of": "^7.0.0",
        "@babel/plugin-transform-function-name": "^7.0.0",
        "@babel/plugin-transform-literals": "^7.0.0",
        "@babel/plugin-transform-modules-commonjs": "^7.0.0",
        "@babel/plugin-transform-object-assign": "^7.0.0",
        "@babel/plugin-transform-parameters": "^7.0.0",
        "@babel/plugin-transform-react-display-name": "^7.0.0",
        "@babel/plugin-transform-react-jsx": "^7.0.0",
        "@babel/plugin-transform-react-jsx-source": "^7.0.0",
        "@babel/plugin-transform-regenerator": "^7.0.0",
        "@babel/plugin-transform-runtime": "^7.0.0",
        "@babel/plugin-transform-shorthand-properties": "^7.0.0",
        "@babel/plugin-transform-spread": "^7.0.0",
        "@babel/plugin-transform-sticky-regex": "^7.0.0",
        "@babel/plugin-transform-template-literals": "^7.0.0",
        "@babel/plugin-transform-typescript": "^7.0.0",
        "@babel/plugin-transform-unicode-regex": "^7.0.0",
        "@babel/template": "^7.0.0",
        "metro-babel7-plugin-react-transform": "0.49.2",
        "react-transform-hmr": "^1.0.4"
      }
    },
    "metro-resolver": {
      "version": "0.45.6",
      "resolved": "https://registry.npmjs.org/metro-resolver/-/metro-resolver-0.45.6.tgz",
      "integrity": "sha512-RY4tqKxSEz4ahLPaJlx30x6vG8HVyLT3w5aUDcyB5B2eQH3ckLnyUYUpd0sT7HFoJ1T5U5DFtWvS3P4yJcRB7A==",
      "requires": {
        "absolute-path": "^0.0.0"
      }
    },
    "metro-source-map": {
      "version": "0.45.6",
      "resolved": "https://registry.npmjs.org/metro-source-map/-/metro-source-map-0.45.6.tgz",
      "integrity": "sha512-FBubSEEitGrvUeuCPVwXTJX7Y1WjFhsUHickqQE+mXplOgREyeZ7o80ffqEWitfsMUQN9385LxIPmAdPzQXLsQ==",
      "requires": {
        "source-map": "^0.5.6"
      }
    },
    "micromatch": {
      "version": "2.3.11",
      "resolved": "https://registry.npmjs.org/micromatch/-/micromatch-2.3.11.tgz",
      "integrity": "sha1-hmd8l9FyCzY0MdBNDRUpO9OMFWU=",
      "requires": {
        "arr-diff": "^2.0.0",
        "array-unique": "^0.2.1",
        "braces": "^1.8.2",
        "expand-brackets": "^0.1.4",
        "extglob": "^0.3.1",
        "filename-regex": "^2.0.0",
        "is-extglob": "^1.0.0",
        "is-glob": "^2.0.1",
        "kind-of": "^3.0.2",
        "normalize-path": "^2.0.1",
        "object.omit": "^2.0.0",
        "parse-glob": "^3.0.4",
        "regex-cache": "^0.4.2"
      },
      "dependencies": {
        "arr-diff": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/arr-diff/-/arr-diff-2.0.0.tgz",
          "integrity": "sha1-jzuCf5Vai9ZpaX5KQlasPOrjVs8=",
          "requires": {
            "arr-flatten": "^1.0.1"
          }
        },
        "kind-of": {
          "version": "3.2.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
          "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
          "requires": {
            "is-buffer": "^1.1.5"
          }
        }
      }
    },
    "mime": {
      "version": "1.6.0",
      "resolved": "https://registry.npmjs.org/mime/-/mime-1.6.0.tgz",
      "integrity": "sha512-x0Vn8spI+wuJ1O6S7gnbaQg8Pxh4NNHb7KSINmEWKiPE4RKOplvijn+NkmYmmRgP68mc70j2EbeTFRsrswaQeg=="
    },
    "mime-db": {
      "version": "1.38.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.38.0.tgz",
      "integrity": "sha512-bqVioMFFzc2awcdJZIzR3HjZFX20QhilVS7hytkKrv7xFAn8bM1gzc/FOX2awLISvWe0PV8ptFKcon+wZ5qYkg=="
    },
    "mime-types": {
      "version": "2.1.22",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.22.tgz",
      "integrity": "sha512-aGl6TZGnhm/li6F7yx82bJiBZwgiEa4Hf6CNr8YO+r5UHr53tSTYZb102zyU50DOWWKeOv0uQLRL0/9EiKWCog==",
      "requires": {
        "mime-db": "~1.38.0"
      }
    },
    "mimic-fn": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/mimic-fn/-/mimic-fn-1.2.0.tgz",
      "integrity": "sha512-jf84uxzwiuiIVKiOLpfYk7N46TSy8ubTonmneY9vrpHNAnp0QBt2BxWV9dO3/j+BoVAb+a5G6YDPW3M5HOdMWQ=="
    },
    "min-document": {
      "version": "2.19.0",
      "resolved": "https://registry.npmjs.org/min-document/-/min-document-2.19.0.tgz",
      "integrity": "sha1-e9KC4/WELtKVu3SM3Z8f+iyCRoU=",
      "requires": {
        "dom-walk": "^0.1.0"
      }
    },
    "minimatch": {
      "version": "3.0.4",
      "resolved": "https://registry.npmjs.org/minimatch/-/minimatch-3.0.4.tgz",
      "integrity": "sha512-yJHVQEhyqPLUTgt9B83PXu6W3rx4MvvHvSUvToogpwoGDOUQ+yDrR0HRot+yOCdCO7u4hX3pWft6kWBBcqh0UA==",
      "requires": {
        "brace-expansion": "^1.1.7"
      }
    },
    "minimist": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/minimist/-/minimist-1.2.0.tgz",
      "integrity": "sha1-o1AIsg9BOD7sH7kU9M1d95omQoQ="
    },
    "mixin-deep": {
      "version": "1.3.1",
      "resolved": "https://registry.npmjs.org/mixin-deep/-/mixin-deep-1.3.1.tgz",
      "integrity": "sha512-8ZItLHeEgaqEvd5lYBXfm4EZSFCX29Jb9K+lAHhDKzReKBQKj3R+7NOF6tjqYi9t4oI8VUfaWITJQm86wnXGNQ==",
      "requires": {
        "for-in": "^1.0.2",
        "is-extendable": "^1.0.1"
      },
      "dependencies": {
        "is-extendable": {
          "version": "1.0.1",
          "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-1.0.1.tgz",
          "integrity": "sha512-arnXMxT1hhoKo9k1LZdmlNyJdDDfy2v0fXjFlmok4+i8ul/6WlbVge9bhM74OpNPQPMGUToDtz+KXa1PneJxOA==",
          "requires": {
            "is-plain-object": "^2.0.4"
          }
        }
      }
    },
    "mkdirp": {
      "version": "0.5.1",
      "resolved": "https://registry.npmjs.org/mkdirp/-/mkdirp-0.5.1.tgz",
      "integrity": "sha1-MAV0OOrGz3+MR2fzhkjWaX11yQM=",
      "requires": {
        "minimist": "0.0.8"
      },
      "dependencies": {
        "minimist": {
          "version": "0.0.8",
          "resolved": "https://registry.npmjs.org/minimist/-/minimist-0.0.8.tgz",
          "integrity": "sha1-hX/Kv8M5fSYluCKCYuhqp6ARsF0="
        }
      }
    },
    "moment": {
      "version": "2.24.0",
      "resolved": "https://registry.npmjs.org/moment/-/moment-2.24.0.tgz",
      "integrity": "sha512-bV7f+6l2QigeBBZSM/6yTNq4P2fNpSWj/0e7jQcy87A8e7o2nAfP/34/2ky5Vw4B9S446EtIhodAzkFCcR4dQg=="
    },
    "moment-timezone": {
      "version": "0.5.23",
      "resolved": "https://registry.npmjs.org/moment-timezone/-/moment-timezone-0.5.23.tgz",
      "integrity": "sha512-WHFH85DkCfiNMDX5D3X7hpNH3/PUhjTGcD0U1SgfBGZxJ3qUmJh5FdvaFjcClxOvB3rzdfj4oRffbI38jEnC1w==",
      "requires": {
        "moment": ">= 2.9.0"
      }
    },
    "morgan": {
      "version": "1.9.1",
      "resolved": "https://registry.npmjs.org/morgan/-/morgan-1.9.1.tgz",
      "integrity": "sha512-HQStPIV4y3afTiCYVxirakhlCfGkI161c76kKFca7Fk1JusM//Qeo1ej2XaMniiNeaZklMVrh3vTtIzpzwbpmA==",
      "requires": {
        "basic-auth": "~2.0.0",
        "debug": "2.6.9",
        "depd": "~1.1.2",
        "on-finished": "~2.3.0",
        "on-headers": "~1.0.1"
      }
    },
    "ms": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.0.0.tgz",
      "integrity": "sha1-VgiurfwAvmwpAd9fmGF4jeDVl8g="
    },
    "mute-stream": {
      "version": "0.0.7",
      "resolved": "https://registry.npmjs.org/mute-stream/-/mute-stream-0.0.7.tgz",
      "integrity": "sha1-MHXOk7whuPq0PhvE2n6BFe0ee6s="
    },
    "nan": {
      "version": "2.12.1",
      "resolved": "https://registry.npmjs.org/nan/-/nan-2.12.1.tgz",
      "integrity": "sha512-JY7V6lRkStKcKTvHO5NVSQRv+RV+FIL5pvDoLiAtSL9pKlC5x9PKQcZDsq7m4FO4d57mkhC6Z+QhAh3Jdk5JFw==",
      "optional": true
    },
    "nanomatch": {
      "version": "1.2.13",
      "resolved": "https://registry.npmjs.org/nanomatch/-/nanomatch-1.2.13.tgz",
      "integrity": "sha512-fpoe2T0RbHwBTBUOftAfBPaDEi06ufaUai0mE6Yn1kacc3SnTErfb/h+X94VXzI64rKFHYImXSvdwGGCmwOqCA==",
      "requires": {
        "arr-diff": "^4.0.0",
        "array-unique": "^0.3.2",
        "define-property": "^2.0.2",
        "extend-shallow": "^3.0.2",
        "fragment-cache": "^0.2.1",
        "is-windows": "^1.0.2",
        "kind-of": "^6.0.2",
        "object.pick": "^1.3.0",
        "regex-not": "^1.0.0",
        "snapdragon": "^0.8.1",
        "to-regex": "^3.0.1"
      },
      "dependencies": {
        "arr-diff": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/arr-diff/-/arr-diff-4.0.0.tgz",
          "integrity": "sha1-1kYQdP6/7HHn4VI1dhoyml3HxSA="
        },
        "array-unique": {
          "version": "0.3.2",
          "resolved": "https://registry.npmjs.org/array-unique/-/array-unique-0.3.2.tgz",
          "integrity": "sha1-qJS3XUvE9s1nnvMkSp/Y9Gri1Cg="
        },
        "extend-shallow": {
          "version": "3.0.2",
          "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-3.0.2.tgz",
          "integrity": "sha1-Jqcarwc7OfshJxcnRhMcJwQCjbg=",
          "requires": {
            "assign-symbols": "^1.0.0",
            "is-extendable": "^1.0.1"
          }
        },
        "is-extendable": {
          "version": "1.0.1",
          "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-1.0.1.tgz",
          "integrity": "sha512-arnXMxT1hhoKo9k1LZdmlNyJdDDfy2v0fXjFlmok4+i8ul/6WlbVge9bhM74OpNPQPMGUToDtz+KXa1PneJxOA==",
          "requires": {
            "is-plain-object": "^2.0.4"
          }
        },
        "kind-of": {
          "version": "6.0.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-6.0.2.tgz",
          "integrity": "sha512-s5kLOcnH0XqDO+FvuaLX8DDjZ18CGFk7VygH40QoKPUQhW4e2rvM0rwUq0t8IQDOwYSeLK01U90OjzBTme2QqA=="
        }
      }
    },
    "native-base": {
      "version": "2.12.0",
      "resolved": "https://registry.npmjs.org/native-base/-/native-base-2.12.0.tgz",
      "integrity": "sha512-3+HP80L7syMi1pGDBymIUgxpaNfoNrd/Pq6knABfwxZN05GClEHRfhAudsdBc88Zi2zGfbJS+VCwqQNl8tWfsA==",
      "requires": {
        "blueimp-md5": "^2.5.0",
        "clamp": "^1.0.1",
        "color": "~1.0.3",
        "fs-extra": "^2.0.0",
        "jest-react-native": "^18.0.0",
        "lodash": "4.17.11",
        "native-base-shoutem-theme": "0.2.3",
        "print-message": "^2.1.0",
        "prop-types": "^15.5.10",
        "react-native-drawer": "2.5.1",
        "react-native-easy-grid": "0.2.1",
        "react-native-keyboard-aware-scroll-view": "0.8.0",
        "react-native-vector-icons": "6.1.0",
        "react-timer-mixin": "^0.13.4",
        "react-tween-state": "^0.1.5",
        "tween-functions": "^1.0.1"
      },
      "dependencies": {
        "color": {
          "version": "1.0.3",
          "resolved": "https://registry.npmjs.org/color/-/color-1.0.3.tgz",
          "integrity": "sha1-5I6DLYXxTvaU+0aIEcLVz+cptV0=",
          "requires": {
            "color-convert": "^1.8.2",
            "color-string": "^1.4.0"
          }
        },
        "fs-extra": {
          "version": "2.1.2",
          "resolved": "https://registry.npmjs.org/fs-extra/-/fs-extra-2.1.2.tgz",
          "integrity": "sha1-BGxwFjzvmq1GsOSn+kZ/si1x3jU=",
          "requires": {
            "graceful-fs": "^4.1.2",
            "jsonfile": "^2.1.0"
          }
        },
        "react-native-vector-icons": {
          "version": "6.1.0",
          "resolved": "https://registry.npmjs.org/react-native-vector-icons/-/react-native-vector-icons-6.1.0.tgz",
          "integrity": "sha512-1GF5I4VWgwnzBtVfAKNgEiR5ziHi5QaKL381wwApMzuiFgIJMNt5XIChuKwKoaiB86s+P5iMcYWxYCyENL96lA==",
          "requires": {
            "lodash": "^4.0.0",
            "prop-types": "^15.6.2",
            "yargs": "^8.0.2"
          }
        },
        "yargs": {
          "version": "8.0.2",
          "resolved": "https://registry.npmjs.org/yargs/-/yargs-8.0.2.tgz",
          "integrity": "sha1-YpmpBVsc78lp/355wdkY3Osiw2A=",
          "requires": {
            "camelcase": "^4.1.0",
            "cliui": "^3.2.0",
            "decamelize": "^1.1.1",
            "get-caller-file": "^1.0.1",
            "os-locale": "^2.0.0",
            "read-pkg-up": "^2.0.0",
            "require-directory": "^2.1.1",
            "require-main-filename": "^1.0.1",
            "set-blocking": "^2.0.0",
            "string-width": "^2.0.0",
            "which-module": "^2.0.0",
            "y18n": "^3.2.1",
            "yargs-parser": "^7.0.0"
          }
        }
      }
    },
    "native-base-shoutem-theme": {
      "version": "0.2.3",
      "resolved": "https://registry.npmjs.org/native-base-shoutem-theme/-/native-base-shoutem-theme-0.2.3.tgz",
      "integrity": "sha512-RitgmvLiQTD5fL5UkiaBYpVQROHlxlP6TzoJjeMUGOxHvwdSFJUnFTfDWZZSxk/YkHP+8CHjnm1XnvmGZvwXKQ==",
      "requires": {
        "hoist-non-react-statics": "^1.0.5",
        "lodash": "4.17.11",
        "prop-types": "^15.5.10"
      },
      "dependencies": {
        "hoist-non-react-statics": {
          "version": "1.2.0",
          "resolved": "https://registry.npmjs.org/hoist-non-react-statics/-/hoist-non-react-statics-1.2.0.tgz",
          "integrity": "sha1-qkSM8JhtVcxAdzsXF0t90GbLfPs="
        }
      }
    },
    "negotiator": {
      "version": "0.6.1",
      "resolved": "https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz",
      "integrity": "sha1-KzJxhOiZIQEXeyhWP7XnECrNDKk="
    },
    "node-fetch": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/node-fetch/-/node-fetch-2.3.0.tgz",
      "integrity": "sha512-MOd8pV3fxENbryESLgVIeaGKrdl+uaYhCSSVkjeOb/31/njTpcis5aWfdqgNlHIrKOLRbMnfPINPOML2CIFeXA=="
    },
    "node-int64": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/node-int64/-/node-int64-0.4.0.tgz",
      "integrity": "sha1-h6kGXNs1XTGC2PlM4RGIuCXGijs="
    },
    "node-modules-regexp": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/node-modules-regexp/-/node-modules-regexp-1.0.0.tgz",
      "integrity": "sha1-jZ2+KJZKSsVxLpExZCEHxx6Q7EA="
    },
    "node-notifier": {
      "version": "5.4.0",
      "resolved": "https://registry.npmjs.org/node-notifier/-/node-notifier-5.4.0.tgz",
      "integrity": "sha512-SUDEb+o71XR5lXSTyivXd9J7fCloE3SyP4lSgt3lU2oSANiox+SxlNRGPjDKrwU1YN3ix2KN/VGGCg0t01rttQ==",
      "requires": {
        "growly": "^1.3.0",
        "is-wsl": "^1.1.0",
        "semver": "^5.5.0",
        "shellwords": "^0.1.1",
        "which": "^1.3.0"
      }
    },
    "noop-fn": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/noop-fn/-/noop-fn-1.0.0.tgz",
      "integrity": "sha1-XzPUfxPSFQ35PgywNmmemC94/78="
    },
    "normalize-package-data": {
      "version": "2.5.0",
      "resolved": "https://registry.npmjs.org/normalize-package-data/-/normalize-package-data-2.5.0.tgz",
      "integrity": "sha512-/5CMN3T0R4XTj4DcGaexo+roZSdSFW/0AOOTROrjxzCG1wrWXEsGbRKevjlIL+ZDE4sZlJr5ED4YW0yqmkK+eA==",
      "requires": {
        "hosted-git-info": "^2.1.4",
        "resolve": "^1.10.0",
        "semver": "2 || 3 || 4 || 5",
        "validate-npm-package-license": "^3.0.1"
      }
    },
    "normalize-path": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/normalize-path/-/normalize-path-2.1.1.tgz",
      "integrity": "sha1-GrKLVW4Zg2Oowab35vogE3/mrtk=",
      "requires": {
        "remove-trailing-separator": "^1.0.1"
      }
    },
    "npm-run-path": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/npm-run-path/-/npm-run-path-2.0.2.tgz",
      "integrity": "sha1-NakjLfo11wZ7TLLd8jV7GHFTbF8=",
      "requires": {
        "path-key": "^2.0.0"
      }
    },
    "npmlog": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/npmlog/-/npmlog-2.0.4.tgz",
      "integrity": "sha1-mLUlMPJRTKkNCexbIsiEZyI3VpI=",
      "requires": {
        "ansi": "~0.3.1",
        "are-we-there-yet": "~1.1.2",
        "gauge": "~1.2.5"
      }
    },
    "nullthrows": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/nullthrows/-/nullthrows-1.1.1.tgz",
      "integrity": "sha512-2vPPEi+Z7WqML2jZYddDIfy5Dqb0r2fze2zTxNNknZaFpVHU3mFB3R+DWeJWGVx0ecvttSGlJTI+WG+8Z4cDWw=="
    },
    "number-is-nan": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/number-is-nan/-/number-is-nan-1.0.1.tgz",
      "integrity": "sha1-CXtgK1NCKlIsGvuHkDGDNpQaAR0="
    },
    "object-assign": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/object-assign/-/object-assign-4.1.1.tgz",
      "integrity": "sha1-IQmtx5ZYh8/AXLvUQsrIv7s2CGM="
    },
    "object-copy": {
      "version": "0.1.0",
      "resolved": "https://registry.npmjs.org/object-copy/-/object-copy-0.1.0.tgz",
      "integrity": "sha1-fn2Fi3gb18mRpBupde04EnVOmYw=",
      "requires": {
        "copy-descriptor": "^0.1.0",
        "define-property": "^0.2.5",
        "kind-of": "^3.0.3"
      },
      "dependencies": {
        "define-property": {
          "version": "0.2.5",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
          "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
          "requires": {
            "is-descriptor": "^0.1.0"
          }
        },
        "kind-of": {
          "version": "3.2.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
          "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
          "requires": {
            "is-buffer": "^1.1.5"
          }
        }
      }
    },
    "object-visit": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/object-visit/-/object-visit-1.0.1.tgz",
      "integrity": "sha1-95xEk68MU3e1n+OdOV5BBC3QRbs=",
      "requires": {
        "isobject": "^3.0.0"
      },
      "dependencies": {
        "isobject": {
          "version": "3.0.1",
          "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
          "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8="
        }
      }
    },
    "object.omit": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/object.omit/-/object.omit-2.0.1.tgz",
      "integrity": "sha1-Gpx0SCnznbuFjHbKNXmuKlTr0fo=",
      "requires": {
        "for-own": "^0.1.4",
        "is-extendable": "^0.1.1"
      }
    },
    "object.pick": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/object.pick/-/object.pick-1.3.0.tgz",
      "integrity": "sha1-h6EKxMFpS9Lhy/U1kaZhQftd10c=",
      "requires": {
        "isobject": "^3.0.1"
      },
      "dependencies": {
        "isobject": {
          "version": "3.0.1",
          "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
          "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8="
        }
      }
    },
    "on-finished": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz",
      "integrity": "sha1-IPEzZIGwg811M3mSoWlxqi2QaUc=",
      "requires": {
        "ee-first": "1.1.1"
      }
    },
    "on-headers": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/on-headers/-/on-headers-1.0.1.tgz",
      "integrity": "sha1-ko9dD0cNSTQmUepnlLCFfBAGk/c="
    },
    "once": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/once/-/once-1.4.0.tgz",
      "integrity": "sha1-WDsap3WWHUsROsF9nFC6753Xa9E=",
      "requires": {
        "wrappy": "1"
      }
    },
    "onetime": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/onetime/-/onetime-2.0.1.tgz",
      "integrity": "sha1-BnQoIw/WdEOyeUsiu6UotoZ5YtQ=",
      "requires": {
        "mimic-fn": "^1.0.0"
      }
    },
    "opencollective-postinstall": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/opencollective-postinstall/-/opencollective-postinstall-2.0.2.tgz",
      "integrity": "sha512-pVOEP16TrAO2/fjej1IdOyupJY8KDUM1CvsaScRbw6oddvpQoOfGk4ywha0HKKVAD6RkW4x6Q+tNBwhf3Bgpuw=="
    },
    "opn": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/opn/-/opn-3.0.3.tgz",
      "integrity": "sha1-ttmec5n3jWXDuq/+8fsojpuFJDo=",
      "requires": {
        "object-assign": "^4.0.1"
      }
    },
    "optimism": {
      "version": "0.6.9",
      "resolved": "https://registry.npmjs.org/optimism/-/optimism-0.6.9.tgz",
      "integrity": "sha512-xoQm2lvXbCA9Kd7SCx6y713Y7sZ6fUc5R6VYpoL5M6svKJbTuvtNopexK8sO8K4s0EOUYHuPN2+yAEsNyRggkQ==",
      "requires": {
        "immutable-tuple": "^0.4.9"
      }
    },
    "optimist": {
      "version": "0.6.1",
      "resolved": "https://registry.npmjs.org/optimist/-/optimist-0.6.1.tgz",
      "integrity": "sha1-2j6nRob6IaGaERwybpDrFaAZZoY=",
      "requires": {
        "minimist": "~0.0.1",
        "wordwrap": "~0.0.2"
      },
      "dependencies": {
        "minimist": {
          "version": "0.0.10",
          "resolved": "https://registry.npmjs.org/minimist/-/minimist-0.0.10.tgz",
          "integrity": "sha1-3j+YVD2/lggr5IrRoMfNqDYwHc8="
        },
        "wordwrap": {
          "version": "0.0.3",
          "resolved": "https://registry.npmjs.org/wordwrap/-/wordwrap-0.0.3.tgz",
          "integrity": "sha1-o9XabNXAvAAI03I0u68b7WMFkQc="
        }
      }
    },
    "options": {
      "version": "0.0.6",
      "resolved": "https://registry.npmjs.org/options/-/options-0.0.6.tgz",
      "integrity": "sha1-7CLTEoBrtT5zF3Pnza788cZDEo8="
    },
    "os-homedir": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/os-homedir/-/os-homedir-1.0.2.tgz",
      "integrity": "sha1-/7xJiDNuDoM94MFox+8VISGqf7M="
    },
    "os-locale": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/os-locale/-/os-locale-2.1.0.tgz",
      "integrity": "sha512-3sslG3zJbEYcaC4YVAvDorjGxc7tv6KVATnLPZONiljsUncvihe9BQoVCEs0RZ1kmf4Hk9OBqlZfJZWI4GanKA==",
      "requires": {
        "execa": "^0.7.0",
        "lcid": "^1.0.0",
        "mem": "^1.1.0"
      }
    },
    "os-tmpdir": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/os-tmpdir/-/os-tmpdir-1.0.2.tgz",
      "integrity": "sha1-u+Z0BseaqFxc/sdm/lc0VV36EnQ="
    },
    "p-finally": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/p-finally/-/p-finally-1.0.0.tgz",
      "integrity": "sha1-P7z7FbiZpEEjs0ttzBi3JDNqLK4="
    },
    "p-limit": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/p-limit/-/p-limit-1.3.0.tgz",
      "integrity": "sha512-vvcXsLAJ9Dr5rQOPk7toZQZJApBl2K4J6dANSsEuh6QI41JYcsS/qhTGa9ErIUUgK3WNQoJYvylxvjqmiqEA9Q==",
      "requires": {
        "p-try": "^1.0.0"
      }
    },
    "p-locate": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/p-locate/-/p-locate-2.0.0.tgz",
      "integrity": "sha1-IKAQOyIqcMj9OcwuWAaA893l7EM=",
      "requires": {
        "p-limit": "^1.1.0"
      }
    },
    "p-try": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/p-try/-/p-try-1.0.0.tgz",
      "integrity": "sha1-y8ec26+P1CKOE/Yh8rGiN8GyB7M="
    },
    "parse-glob": {
      "version": "3.0.4",
      "resolved": "https://registry.npmjs.org/parse-glob/-/parse-glob-3.0.4.tgz",
      "integrity": "sha1-ssN2z7EfNVE7rdFz7wu246OIORw=",
      "requires": {
        "glob-base": "^0.3.0",
        "is-dotfile": "^1.0.0",
        "is-extglob": "^1.0.0",
        "is-glob": "^2.0.0"
      }
    },
    "parse-json": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/parse-json/-/parse-json-2.2.0.tgz",
      "integrity": "sha1-9ID0BDTvgHQfhGkJn43qGPVaTck=",
      "requires": {
        "error-ex": "^1.2.0"
      }
    },
    "parse-node-version": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/parse-node-version/-/parse-node-version-1.0.1.tgz",
      "integrity": "sha512-3YHlOa/JgH6Mnpr05jP9eDG254US9ek25LyIxZlDItp2iJtwyaXQb57lBYLdT3MowkUFYEV2XXNAYIPlESvJlA=="
    },
    "parseurl": {
      "version": "1.3.2",
      "resolved": "https://registry.npmjs.org/parseurl/-/parseurl-1.3.2.tgz",
      "integrity": "sha1-/CidTtiZMRlGDBViUyYs3I3mW/M="
    },
    "pascalcase": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/pascalcase/-/pascalcase-0.1.1.tgz",
      "integrity": "sha1-s2PlXoAGym/iF4TS2yK9FdeRfxQ="
    },
    "path-exists": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/path-exists/-/path-exists-3.0.0.tgz",
      "integrity": "sha1-zg6+ql94yxiSXqfYENe1mwEP1RU="
    },
    "path-is-absolute": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/path-is-absolute/-/path-is-absolute-1.0.1.tgz",
      "integrity": "sha1-F0uSaHNVNP+8es5r9TpanhtcX18="
    },
    "path-key": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/path-key/-/path-key-2.0.1.tgz",
      "integrity": "sha1-QRyttXTFoUDTpLGRDUDYDMn0C0A="
    },
    "path-parse": {
      "version": "1.0.6",
      "resolved": "https://registry.npmjs.org/path-parse/-/path-parse-1.0.6.tgz",
      "integrity": "sha512-GSmOT2EbHrINBf9SR7CDELwlJ8AENk3Qn7OikK4nFYAu3Ote2+JYNVvkpAEQm3/TLNEJFD/xZJjzyxg3KBWOzw=="
    },
    "path-to-regexp": {
      "version": "1.7.0",
      "resolved": "https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-1.7.0.tgz",
      "integrity": "sha1-Wf3g9DW62suhA6hOnTvGTpa5k30=",
      "requires": {
        "isarray": "0.0.1"
      },
      "dependencies": {
        "isarray": {
          "version": "0.0.1",
          "resolved": "https://registry.npmjs.org/isarray/-/isarray-0.0.1.tgz",
          "integrity": "sha1-ihis/Kmo9Bd+Cav8YDiTmwXR7t8="
        }
      }
    },
    "path-type": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/path-type/-/path-type-2.0.0.tgz",
      "integrity": "sha1-8BLMuEFbcJb8LaoQVMPXI4lZTHM=",
      "requires": {
        "pify": "^2.0.0"
      }
    },
    "pegjs": {
      "version": "0.10.0",
      "resolved": "https://registry.npmjs.org/pegjs/-/pegjs-0.10.0.tgz",
      "integrity": "sha1-z4uvrm7d/0tafvsYUmnqr0YQ3b0="
    },
    "performance-now": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/performance-now/-/performance-now-2.1.0.tgz",
      "integrity": "sha1-Ywn04OX6kT7BxpMHrjZLSzd8nns="
    },
    "pify": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/pify/-/pify-2.3.0.tgz",
      "integrity": "sha1-7RQaasBDqEnqWISY59yosVMw6Qw="
    },
    "pirates": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/pirates/-/pirates-4.0.1.tgz",
      "integrity": "sha512-WuNqLTbMI3tmfef2TKxlQmAiLHKtFhlsCZnPIpuv2Ow0RDVO8lfy1Opf4NUzlMXLjPl+Men7AuVdX6TA+s+uGA==",
      "requires": {
        "node-modules-regexp": "^1.0.0"
      }
    },
    "pkg-dir": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/pkg-dir/-/pkg-dir-2.0.0.tgz",
      "integrity": "sha1-9tXREJ4Z1j7fQo4L1X4Sd3YVM0s=",
      "requires": {
        "find-up": "^2.1.0"
      }
    },
    "pkg-up": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/pkg-up/-/pkg-up-2.0.0.tgz",
      "integrity": "sha1-yBmscoBZpGHKscOImivjxJoATX8=",
      "requires": {
        "find-up": "^2.1.0"
      }
    },
    "plist": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/plist/-/plist-3.0.1.tgz",
      "integrity": "sha512-GpgvHHocGRyQm74b6FWEZZVRroHKE1I0/BTjAmySaohK+cUn+hZpbqXkc3KWgW3gQYkqcQej35FohcT0FRlkRQ==",
      "requires": {
        "base64-js": "^1.2.3",
        "xmlbuilder": "^9.0.7",
        "xmldom": "0.1.x"
      }
    },
    "plugin-error": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/plugin-error/-/plugin-error-0.1.2.tgz",
      "integrity": "sha1-O5uzM1zPAPQl4HQ34ZJ2ln2kes4=",
      "requires": {
        "ansi-cyan": "^0.1.1",
        "ansi-red": "^0.1.1",
        "arr-diff": "^1.0.1",
        "arr-union": "^2.0.1",
        "extend-shallow": "^1.1.2"
      }
    },
    "popper.js": {
      "version": "1.14.7",
      "resolved": "https://registry.npmjs.org/popper.js/-/popper.js-1.14.7.tgz",
      "integrity": "sha512-4q1hNvoUre/8srWsH7hnoSJ5xVmIL4qgz+s4qf2TnJIMyZFUFMGH+9vE7mXynAlHSZ/NdTmmow86muD0myUkVQ=="
    },
    "posix-character-classes": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/posix-character-classes/-/posix-character-classes-0.1.1.tgz",
      "integrity": "sha1-AerA/jta9xoqbAL+q7jB/vfgDqs="
    },
    "pouchdb-collections": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/pouchdb-collections/-/pouchdb-collections-1.0.1.tgz",
      "integrity": "sha1-/mOhfal3YRq+98uAJssalVP9g1k="
    },
    "preserve": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/preserve/-/preserve-0.2.0.tgz",
      "integrity": "sha1-gV7R9uvGWSb4ZbMQwHE7yzMVzks="
    },
    "pretty-format": {
      "version": "23.6.0",
      "resolved": "https://registry.npmjs.org/pretty-format/-/pretty-format-23.6.0.tgz",
      "integrity": "sha512-zf9NV1NSlDLDjycnwm6hpFATCGl/K1lt0R/GdkAK2O5LN/rwJoB+Mh93gGJjut4YbmecbfgLWVGSTCr0Ewvvbw==",
      "requires": {
        "ansi-regex": "^3.0.0",
        "ansi-styles": "^3.2.0"
      },
      "dependencies": {
        "ansi-regex": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-3.0.0.tgz",
          "integrity": "sha1-7QMXwyIGT3lGbAKWa922Bas32Zg="
        }
      }
    },
    "print-message": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/print-message/-/print-message-2.1.0.tgz",
      "integrity": "sha1-tViO0IsOG/d6x7y1y3gASvr5qJE=",
      "requires": {
        "chalk": "1.1.1"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "2.2.1",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz",
          "integrity": "sha1-tDLdM1i2NM914eRmQ2gkBTPB3b4="
        },
        "chalk": {
          "version": "1.1.1",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-1.1.1.tgz",
          "integrity": "sha1-UJr7ZwZudJn36zU1x3RFdyri0Bk=",
          "requires": {
            "ansi-styles": "^2.1.0",
            "escape-string-regexp": "^1.0.2",
            "has-ansi": "^2.0.0",
            "strip-ansi": "^3.0.0",
            "supports-color": "^2.0.0"
          }
        }
      }
    },
    "private": {
      "version": "0.1.8",
      "resolved": "https://registry.npmjs.org/private/-/private-0.1.8.tgz",
      "integrity": "sha512-VvivMrbvd2nKkiG38qjULzlc+4Vx4wm/whI9pQD35YrARNnhxeiRktSOhSukRLFNlzg6Br/cJPet5J/u19r/mg=="
    },
    "process": {
      "version": "0.5.2",
      "resolved": "https://registry.npmjs.org/process/-/process-0.5.2.tgz",
      "integrity": "sha1-FjjYqONML0QKkduVq5rrZ3/Bhc8="
    },
    "process-nextick-args": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-2.0.0.tgz",
      "integrity": "sha512-MtEC1TqN0EU5nephaJ4rAtThHtC86dNN9qCuEhtshvpVBkAW5ZO7BASN9REnF9eoXGcRub+pFuKEpOHE+HbEMw=="
    },
    "promise": {
      "version": "7.3.1",
      "resolved": "https://registry.npmjs.org/promise/-/promise-7.3.1.tgz",
      "integrity": "sha512-nolQXZ/4L+bP/UGlkfaIujX9BKxGwmQ9OT4mOt5yvy8iK1h3wqTEJCijzGANTCCl9nWjY41juyAn2K3Q1hLLTg==",
      "requires": {
        "asap": "~2.0.3"
      }
    },
    "prop-types": {
      "version": "15.7.2",
      "resolved": "https://registry.npmjs.org/prop-types/-/prop-types-15.7.2.tgz",
      "integrity": "sha512-8QQikdH7//R2vurIJSutZ1smHYTcLpRWEOlHnzcWHmBYrOGUysKwSsrC89BCiFj3CbrfJ/nXFdJepOVrY1GCHQ==",
      "requires": {
        "loose-envify": "^1.4.0",
        "object-assign": "^4.1.1",
        "react-is": "^16.8.1"
      }
    },
    "property-expr": {
      "version": "1.5.1",
      "resolved": "https://registry.npmjs.org/property-expr/-/property-expr-1.5.1.tgz",
      "integrity": "sha512-CGuc0VUTGthpJXL36ydB6jnbyOf/rAHFvmVrJlH+Rg0DqqLFQGAP6hIaxD/G0OAmBJPhXDHuEJigrp0e0wFV6g=="
    },
    "pseudomap": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/pseudomap/-/pseudomap-1.0.2.tgz",
      "integrity": "sha1-8FKijacOYYkX7wqKw0wa5aaChrM="
    },
    "punycode": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.1.1.tgz",
      "integrity": "sha512-XRsRjdf+j5ml+y/6GKHPZbrF/8p2Yga0JPtdqTIY2Xe5ohJPD9saDJJLPvp9+NSBprVvevdXZybnj2cv8OEd0A=="
    },
    "qs": {
      "version": "6.6.0",
      "resolved": "https://registry.npmjs.org/qs/-/qs-6.6.0.tgz",
      "integrity": "sha512-KIJqT9jQJDQx5h5uAVPimw6yVg2SekOKu959OCtktD3FjzbpvaPr8i4zzg07DOMz+igA4W/aNM7OV8H37pFYfA=="
    },
    "query-string": {
      "version": "6.2.0",
      "resolved": "https://registry.npmjs.org/query-string/-/query-string-6.2.0.tgz",
      "integrity": "sha512-5wupExkIt8RYL4h/FE+WTg3JHk62e6fFPWtAZA9J5IWK1PfTfKkMS93HBUHcFpeYi9KsY5pFbh+ldvEyaz5MyA==",
      "requires": {
        "decode-uri-component": "^0.2.0",
        "strict-uri-encode": "^2.0.0"
      }
    },
    "raf": {
      "version": "3.4.1",
      "resolved": "https://registry.npmjs.org/raf/-/raf-3.4.1.tgz",
      "integrity": "sha512-Sq4CW4QhwOHE8ucn6J34MqtZCeWFP2aQSmrlroYgqAV1PjStIhJXxYuTgUIfkEk7zTLjmIjLmU5q+fbD1NnOJA==",
      "requires": {
        "performance-now": "^2.1.0"
      }
    },
    "randomatic": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/randomatic/-/randomatic-3.1.1.tgz",
      "integrity": "sha512-TuDE5KxZ0J461RVjrJZCJc+J+zCkTb1MbH9AQUq68sMhOMcy9jLcb3BrZKgp9q9Ncltdg4QVqWrH02W2EFFVYw==",
      "requires": {
        "is-number": "^4.0.0",
        "kind-of": "^6.0.0",
        "math-random": "^1.0.1"
      },
      "dependencies": {
        "is-number": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/is-number/-/is-number-4.0.0.tgz",
          "integrity": "sha512-rSklcAIlf1OmFdyAqbnWTLVelsQ58uvZ66S/ZyawjWqIviTWCjg2PzVGw8WUA+nNuPTqb4wgA+NszrJ+08LlgQ=="
        },
        "kind-of": {
          "version": "6.0.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-6.0.2.tgz",
          "integrity": "sha512-s5kLOcnH0XqDO+FvuaLX8DDjZ18CGFk7VygH40QoKPUQhW4e2rvM0rwUq0t8IQDOwYSeLK01U90OjzBTme2QqA=="
        }
      }
    },
    "range-parser": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/range-parser/-/range-parser-1.2.0.tgz",
      "integrity": "sha1-9JvmtIeJTdxA3MlKMi9hEJLgDV4="
    },
    "react": {
      "version": "16.5.0",
      "resolved": "https://registry.npmjs.org/react/-/react-16.5.0.tgz",
      "integrity": "sha512-nw/yB/L51kA9PsAy17T1JrzzGRk+BlFCJwFF7p+pwVxgqwPjYNeZEkkH7LXn9dmflolrYMXLWMTkQ77suKPTNQ==",
      "requires": {
        "loose-envify": "^1.1.0",
        "object-assign": "^4.1.1",
        "prop-types": "^15.6.2",
        "schedule": "^0.3.0"
      }
    },
    "react-apollo": {
      "version": "2.5.1",
      "resolved": "https://registry.npmjs.org/react-apollo/-/react-apollo-2.5.1.tgz",
      "integrity": "sha512-obXPcmjJ5O75UkoizcsIbe0PXAXKRqm+SwNu059HQInB3FAab9PIn4wd/KglpPNiB9JXHe8OJDov0lFMcBbHEQ==",
      "requires": {
        "apollo-utilities": "^1.2.1",
        "hoist-non-react-statics": "^3.0.0",
        "lodash.isequal": "^4.5.0",
        "prop-types": "^15.6.0",
        "ts-invariant": "^0.2.1",
        "tslib": "^1.9.3"
      },
      "dependencies": {
        "hoist-non-react-statics": {
          "version": "3.3.0",
          "resolved": "https://registry.npmjs.org/hoist-non-react-statics/-/hoist-non-react-statics-3.3.0.tgz",
          "integrity": "sha512-0XsbTXxgiaCDYDIWFcwkmerZPSwywfUqYmwT4jzewKTQSWoE6FCMoUVOeBJWK3E/CrWbxRG3m5GzY4lnIwGRBA==",
          "requires": {
            "react-is": "^16.7.0"
          }
        }
      }
    },
    "react-clone-referenced-element": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/react-clone-referenced-element/-/react-clone-referenced-element-1.1.0.tgz",
      "integrity": "sha512-FKOsfKbBkPxYE8576EM6uAfHC4rnMpLyH6/TJUL4WcHUEB3EUn8AxPjnnV/IiwSSzsClvHYK+sDELKN/EJ0WYg=="
    },
    "react-deep-force-update": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/react-deep-force-update/-/react-deep-force-update-1.1.2.tgz",
      "integrity": "sha512-WUSQJ4P/wWcusaH+zZmbECOk7H5N2pOIl0vzheeornkIMhu+qrNdGFm0bDZLCb0hSF0jf/kH1SgkNGfBdTc4wA=="
    },
    "react-devtools-core": {
      "version": "3.3.4",
      "resolved": "https://registry.npmjs.org/react-devtools-core/-/react-devtools-core-3.3.4.tgz",
      "integrity": "sha512-6lsBDRInT9jU8Ya8bnKWJSsnaGg/xk1ZSfvhc/dHc3n2CUTMfGlqm2tGeZQ9WEoe0Y2K7Lg90Kvb1E8anLePaQ==",
      "requires": {
        "shell-quote": "^1.6.1",
        "ws": "^3.3.1"
      },
      "dependencies": {
        "ultron": {
          "version": "1.1.1",
          "resolved": "https://registry.npmjs.org/ultron/-/ultron-1.1.1.tgz",
          "integrity": "sha512-UIEXBNeYmKptWH6z8ZnqTeS8fV74zG0/eRU9VGkpzz+LIJNs8W/zM/L+7ctCkRrgbNnnR0xxw4bKOr0cW0N0Og=="
        },
        "ws": {
          "version": "3.3.3",
          "resolved": "https://registry.npmjs.org/ws/-/ws-3.3.3.tgz",
          "integrity": "sha512-nnWLa/NwZSt4KQJu51MYlCcSQ5g7INpOrOMt4XV8j4dqTXdmlUmSHQ8/oLC069ckre0fRsgfvsKwbTdtKLCDkA==",
          "requires": {
            "async-limiter": "~1.0.0",
            "safe-buffer": "~5.1.0",
            "ultron": "~1.1.0"
          }
        }
      }
    },
    "react-fast-compare": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/react-fast-compare/-/react-fast-compare-2.0.4.tgz",
      "integrity": "sha512-suNP+J1VU1MWFKcyt7RtjiSWUjvidmQSlqu+eHslq+342xCbGTYmC0mEhPCOHxlW0CywylOC1u2DFAT+bv4dBw=="
    },
    "react-is": {
      "version": "16.8.2",
      "resolved": "https://registry.npmjs.org/react-is/-/react-is-16.8.2.tgz",
      "integrity": "sha512-D+NxhSR2HUCjYky1q1DwpNUD44cDpUXzSmmFyC3ug1bClcU/iDNy0YNn1iwme28fn+NFhpA13IndOd42CrFb+Q=="
    },
    "react-lifecycles-compat": {
      "version": "3.0.4",
      "resolved": "https://registry.npmjs.org/react-lifecycles-compat/-/react-lifecycles-compat-3.0.4.tgz",
      "integrity": "sha512-fBASbA6LnOU9dOU2eW7aQ8xmYBSXUIWr+UmF9b1efZBazGNO+rcXT/icdKnYm2pTwcRylVUYwW7H1PHfLekVzA=="
    },
    "react-native": {
      "version": "https://github.com/expo/react-native/archive/sdk-32.0.0.tar.gz",
      "integrity": "sha512-+taJh7bN2owmwaZpJUrNpHdmPAL6ZynNCZj15uLQgjaPFq0ZBIG2ZWuSJ48eGoUjAb3lrWxkmLlHb2eJFXc7sQ==",
      "requires": {
        "absolute-path": "^0.0.0",
        "art": "^0.10.0",
        "base64-js": "^1.1.2",
        "chalk": "^1.1.1",
        "commander": "^2.9.0",
        "compression": "^1.7.1",
        "connect": "^3.6.5",
        "create-react-class": "^15.6.3",
        "debug": "^2.2.0",
        "denodeify": "^1.2.1",
        "envinfo": "^5.7.0",
        "errorhandler": "^1.5.0",
        "escape-string-regexp": "^1.0.5",
        "event-target-shim": "^1.0.5",
        "fbjs": "0.8.17",
        "fbjs-scripts": "^0.8.1",
        "fs-extra": "^1.0.0",
        "glob": "^7.1.1",
        "graceful-fs": "^4.1.3",
        "inquirer": "^3.0.6",
        "lodash": "^4.17.5",
        "metro": "^0.45.6",
        "metro-babel-register": "^0.45.6",
        "metro-core": "^0.45.6",
        "metro-memory-fs": "^0.45.6",
        "mime": "^1.3.4",
        "minimist": "^1.2.0",
        "mkdirp": "^0.5.1",
        "morgan": "^1.9.0",
        "node-fetch": "^2.2.0",
        "node-notifier": "^5.2.1",
        "npmlog": "^2.0.4",
        "opn": "^3.0.2",
        "optimist": "^0.6.1",
        "plist": "^3.0.0",
        "pretty-format": "^4.2.1",
        "promise": "^7.1.1",
        "prop-types": "^15.5.8",
        "react-clone-referenced-element": "^1.0.1",
        "react-devtools-core": "3.3.4",
        "react-timer-mixin": "^0.13.2",
        "regenerator-runtime": "^0.11.0",
        "rimraf": "^2.5.4",
        "semver": "^5.0.3",
        "serve-static": "^1.13.1",
        "shell-quote": "1.6.1",
        "stacktrace-parser": "^0.1.3",
        "ws": "^1.1.0",
        "xcode": "^0.9.1",
        "xmldoc": "^0.4.0",
        "yargs": "^9.0.0"
      },
      "dependencies": {
        "pretty-format": {
          "version": "4.3.1",
          "resolved": "https://registry.npmjs.org/pretty-format/-/pretty-format-4.3.1.tgz",
          "integrity": "sha1-UwvlxCs8BbNkFKeipDN6qArNDo0="
        }
      }
    },
    "react-native-branch": {
      "version": "2.2.5",
      "resolved": "https://registry.npmjs.org/react-native-branch/-/react-native-branch-2.2.5.tgz",
      "integrity": "sha1-QHTdY7SXPmOX2c5Q6XtXx3pRjp0="
    },
    "react-native-drawer": {
      "version": "2.5.1",
      "resolved": "https://registry.npmjs.org/react-native-drawer/-/react-native-drawer-2.5.1.tgz",
      "integrity": "sha512-cxcQNbSWy5sbGi7anSVp6EDr6JarOBMY9lbFOeLFeVYbONiudoqRKbgEsSDgSw3/LFCLvUXK5zdjXCOedeytxQ==",
      "requires": {
        "prop-types": "^15.5.8",
        "tween-functions": "^1.0.1"
      }
    },
    "react-native-easy-grid": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/react-native-easy-grid/-/react-native-easy-grid-0.2.1.tgz",
      "integrity": "sha512-u90U4lf5L/PUmq7HoczFKgyElmBCpb3gu21TOWL7pq4gSH2Hz0EGm1Bgu0SQacO9v6jfQbS7JfE+xtMg6MHluQ==",
      "requires": {
        "lodash": "4.17.11"
      }
    },
    "react-native-elements": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/react-native-elements/-/react-native-elements-1.0.0.tgz",
      "integrity": "sha512-m5kzFCOIEyoY5qTYn6c2n9AYodn1Ol4tVNEaQ5wVXwaDDNyafshqXQ3QmYUWW8yfogMmCdLSi0KfQmYQNElEtA==",
      "requires": {
        "color": "^3.1.0",
        "hoist-non-react-statics": "^3.1.0",
        "lodash.merge": "^4.6.1",
        "opencollective-postinstall": "^2.0.0",
        "prop-types": "^15.5.8",
        "react-native-ratings": "^6.3.0",
        "react-native-status-bar-height": "^2.2.0"
      },
      "dependencies": {
        "color": {
          "version": "3.1.0",
          "resolved": "https://registry.npmjs.org/color/-/color-3.1.0.tgz",
          "integrity": "sha512-CwyopLkuRYO5ei2EpzpIh6LqJMt6Mt+jZhO5VI5f/wJLZriXQE32/SSqzmrh+QB+AZT81Cj8yv+7zwToW8ahZg==",
          "requires": {
            "color-convert": "^1.9.1",
            "color-string": "^1.5.2"
          }
        },
        "hoist-non-react-statics": {
          "version": "3.3.0",
          "resolved": "https://registry.npmjs.org/hoist-non-react-statics/-/hoist-non-react-statics-3.3.0.tgz",
          "integrity": "sha512-0XsbTXxgiaCDYDIWFcwkmerZPSwywfUqYmwT4jzewKTQSWoE6FCMoUVOeBJWK3E/CrWbxRG3m5GzY4lnIwGRBA==",
          "requires": {
            "react-is": "^16.7.0"
          }
        }
      }
    },
    "react-native-gesture-handler": {
      "version": "1.0.16",
      "resolved": "https://registry.npmjs.org/react-native-gesture-handler/-/react-native-gesture-handler-1.0.16.tgz",
      "integrity": "sha512-KhUjDaiGKESfVa/lywuYfdZ2pomPC4q/dRQo18qlSZuRxEiOCxzSo9Q1TV7JK3PpyyMEXpsU04kYSSVypWiSxg==",
      "requires": {
        "hoist-non-react-statics": "^2.3.1",
        "invariant": "^2.2.2",
        "prop-types": "^15.5.10"
      }
    },
    "react-native-iphone-x-helper": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/react-native-iphone-x-helper/-/react-native-iphone-x-helper-1.2.0.tgz",
      "integrity": "sha512-xIeTo4s77wwKgBZLVRIZC9tM9/PkXS46Ul76NXmvmixEb3ZwqGdQesR3zRiLMOoIdfOURB6N9bba9po7+x9Bag=="
    },
    "react-native-keyboard-aware-scroll-view": {
      "version": "0.8.0",
      "resolved": "https://registry.npmjs.org/react-native-keyboard-aware-scroll-view/-/react-native-keyboard-aware-scroll-view-0.8.0.tgz",
      "integrity": "sha512-gPfhgHQI/z7Cc5aeNOEmK0b250QkAeU6V+4oH8EC7mmFneEKn6MAIDjpoiwqt6bV+lFJPABXfx9MtrRmtCeJ/Q==",
      "requires": {
        "prop-types": "^15.6.2",
        "react-native-iphone-x-helper": "^1.0.3"
      }
    },
    "react-native-material-buttons": {
      "version": "0.5.0",
      "resolved": "https://registry.npmjs.org/react-native-material-buttons/-/react-native-material-buttons-0.5.0.tgz",
      "integrity": "sha1-qys+P8P1AMpxP1Hp11l4r/YCFSo=",
      "requires": {
        "prop-types": "^15.5.9",
        "react-native-material-ripple": "^0.7.0"
      },
      "dependencies": {
        "react-native-material-ripple": {
          "version": "0.7.5",
          "resolved": "https://registry.npmjs.org/react-native-material-ripple/-/react-native-material-ripple-0.7.5.tgz",
          "integrity": "sha1-4q9REGgFMvFK6jw6Q4JHvi/+9lk=",
          "requires": {
            "prop-types": "^15.5.10"
          }
        }
      }
    },
    "react-native-material-dropdown": {
      "version": "0.11.1",
      "resolved": "https://registry.npmjs.org/react-native-material-dropdown/-/react-native-material-dropdown-0.11.1.tgz",
      "integrity": "sha1-wP5DSo5heUHvkQukTS8HyPN1hP4=",
      "requires": {
        "prop-types": "^15.5.9",
        "react-native-material-buttons": "^0.5.0",
        "react-native-material-ripple": "^0.8.0",
        "react-native-material-textfield": "^0.12.0"
      }
    },
    "react-native-material-ripple": {
      "version": "0.8.0",
      "resolved": "https://registry.npmjs.org/react-native-material-ripple/-/react-native-material-ripple-0.8.0.tgz",
      "integrity": "sha1-uMJOb96iryoh6EaLH0CzVIMBni8=",
      "requires": {
        "prop-types": "^15.5.10"
      }
    },
    "react-native-material-textfield": {
      "version": "0.12.0",
      "resolved": "https://registry.npmjs.org/react-native-material-textfield/-/react-native-material-textfield-0.12.0.tgz",
      "integrity": "sha1-P7oZ12q4n2cFLIHgghUvwkPYKj8=",
      "requires": {
        "prop-types": "^15.5.9"
      }
    },
    "react-native-ratings": {
      "version": "6.3.0",
      "resolved": "https://registry.npmjs.org/react-native-ratings/-/react-native-ratings-6.3.0.tgz",
      "integrity": "sha512-vjzsTM4L3J3n0X9fJMFSJ3ZUqbPp2ExZtgg/Ycst9SqwiHCOouEwEpEcLF+KzYp3MgL62ZACIKSUyfWIIdBafA==",
      "requires": {
        "lodash": "^4.17.4",
        "prop-types": "^15.5.10"
      }
    },
    "react-native-reanimated": {
      "version": "1.0.0-alpha.11",
      "resolved": "https://registry.npmjs.org/react-native-reanimated/-/react-native-reanimated-1.0.0-alpha.11.tgz",
      "integrity": "sha512-lDakjY8CXmZiSN71hyc276b3d7M9mKV9ZyYw4W/rTnnJbgBFaqdIxSHq4S4LxSbVqpAoQMfUJqPTE0BKbAz7Aw=="
    },
    "react-native-safe-area-view": {
      "version": "0.13.0",
      "resolved": "https://registry.npmjs.org/react-native-safe-area-view/-/react-native-safe-area-view-0.13.0.tgz",
      "integrity": "sha512-k8F527IHtQrRSynibY49ryrHLtOvjtE1GqLxULMnH0PIjSITe+nbq4nx75xrZTwd7sSoLbX6lgroZTG8AO3iUw==",
      "requires": {
        "hoist-non-react-statics": "^2.3.1"
      }
    },
    "react-native-safe-module": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/react-native-safe-module/-/react-native-safe-module-1.2.0.tgz",
      "integrity": "sha1-ojgkyiTtwpAZE2lKdmRkdRE9Vw0=",
      "requires": {
        "dedent": "^0.6.0"
      }
    },
    "react-native-screens": {
      "version": "1.0.0-alpha.22",
      "resolved": "https://registry.npmjs.org/react-native-screens/-/react-native-screens-1.0.0-alpha.22.tgz",
      "integrity": "sha512-kSyAt0AeVU6N7ZonfV6dP6iZF8B7Bce+tk3eujXhzBGsLg0VSLnU7uE9VqJF0xdQrHR91ZjGgVMieo/8df9KTA=="
    },
    "react-native-status-bar-height": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/react-native-status-bar-height/-/react-native-status-bar-height-2.2.0.tgz",
      "integrity": "sha512-4WJpyZirzeMHyZiyNEy4LnSPOtuLRVy3+28Rhz7ffrjCVcc5RFcC0HVjFnkwfuhcTyXIDtzPG6canJkXzbTtBA=="
    },
    "react-native-svg": {
      "version": "8.0.10",
      "resolved": "https://registry.npmjs.org/react-native-svg/-/react-native-svg-8.0.10.tgz",
      "integrity": "sha512-gsG5GUdvlox67+ohLnq3tZSqiYBmz4M5lKKeUfnJZ8EPrMMS5ZgaVj7Zcccee1VvINS5xQaoenUJdha/GEo34w==",
      "requires": {
        "color": "^2.0.1",
        "lodash": "^4.16.6",
        "pegjs": "^0.10.0"
      }
    },
    "react-native-tab-view": {
      "version": "1.3.2",
      "resolved": "https://registry.npmjs.org/react-native-tab-view/-/react-native-tab-view-1.3.2.tgz",
      "integrity": "sha512-2U+HxDQdjzExoC6gZ+wUhC8v8JjntppsFVU4v4pRvC/1dkN7DJv1k8UEy9+p7ucEaNrcAzu/j5N09Jf4qG36vw==",
      "requires": {
        "prop-types": "^15.6.1"
      }
    },
    "react-native-vector-icons": {
      "version": "6.3.0",
      "resolved": "https://registry.npmjs.org/react-native-vector-icons/-/react-native-vector-icons-6.3.0.tgz",
      "integrity": "sha512-3Rf77BC1BhCpHkCitq4hDAEyaAR7Won5qrHU3fBoZzkEsI5oFTCfvnMDYzCx7XDW5Xn0u/Yg7JD9USynAOYVYA==",
      "requires": {
        "lodash": "^4.0.0",
        "prop-types": "^15.6.2",
        "yargs": "^8.0.2"
      },
      "dependencies": {
        "yargs": {
          "version": "8.0.2",
          "resolved": "https://registry.npmjs.org/yargs/-/yargs-8.0.2.tgz",
          "integrity": "sha1-YpmpBVsc78lp/355wdkY3Osiw2A=",
          "requires": {
            "camelcase": "^4.1.0",
            "cliui": "^3.2.0",
            "decamelize": "^1.1.1",
            "get-caller-file": "^1.0.1",
            "os-locale": "^2.0.0",
            "read-pkg-up": "^2.0.0",
            "require-directory": "^2.1.1",
            "require-main-filename": "^1.0.1",
            "set-blocking": "^2.0.0",
            "string-width": "^2.0.0",
            "which-module": "^2.0.0",
            "y18n": "^3.2.1",
            "yargs-parser": "^7.0.0"
          }
        }
      }
    },
    "react-native-view-shot": {
      "version": "2.5.0",
      "resolved": "https://registry.npmjs.org/react-native-view-shot/-/react-native-view-shot-2.5.0.tgz",
      "integrity": "sha512-xFJA+N7wh8Ik/17I4QB24e0a0L3atg1ScVehvtYR5UBTgHdzTFA0ZylvXp9gkZt7V+AT5Pni0H3NQItpqSKFoQ=="
    },
    "react-navigation": {
      "version": "3.3.2",
      "resolved": "https://registry.npmjs.org/react-navigation/-/react-navigation-3.3.2.tgz",
      "integrity": "sha512-XETRxwPGHvJh3LKkAhX5b2sg2u9QiMegmEd0H5O0GWjqYrfJ7LcwzeM0273OfwcpR5lyl+hkCVPMkM+i1xFnVw==",
      "requires": {
        "@react-navigation/core": "3.1.1",
        "@react-navigation/native": "3.1.5",
        "react-navigation-drawer": "1.2.0",
        "react-navigation-stack": "1.0.10",
        "react-navigation-tabs": "1.0.2"
      }
    },
    "react-navigation-drawer": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/react-navigation-drawer/-/react-navigation-drawer-1.2.0.tgz",
      "integrity": "sha512-78idNMJpOGzn0jHej69yTIiqJWdCVdMy2sBtppcdnT+DHeZXQDamTuGurjluf/2WyNB2xAXipIk4N4NnvqRfvw==",
      "requires": {
        "react-native-tab-view": "^1.2.0"
      }
    },
    "react-navigation-stack": {
      "version": "1.0.10",
      "resolved": "https://registry.npmjs.org/react-navigation-stack/-/react-navigation-stack-1.0.10.tgz",
      "integrity": "sha512-p+1oJ6lQYzblidOopIX0Tt+0ZvzaTyoPrBU9erMI04LEoa37BovYpWd1NXBIkV5+wfRt/o5R2x+RZ3LUeWpjeA=="
    },
    "react-navigation-tabs": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/react-navigation-tabs/-/react-navigation-tabs-1.0.2.tgz",
      "integrity": "sha512-ffWPVdo+L0GLbQlLAzH7ITYqh9V9NdqT/juj8QtESH5/2yUqfvqTxQoSowvFIrtiIHHFH6tLoQy1sZZciTxmeg==",
      "requires": {
        "hoist-non-react-statics": "^2.5.0",
        "prop-types": "^15.6.1",
        "react-lifecycles-compat": "^3.0.4",
        "react-native-tab-view": "^1.0.0"
      }
    },
    "react-popper": {
      "version": "0.10.4",
      "resolved": "https://registry.npmjs.org/react-popper/-/react-popper-0.10.4.tgz",
      "integrity": "sha1-rypBXqIike3VBGeNev2opu4ylao=",
      "requires": {
        "popper.js": "^1.14.1",
        "prop-types": "^15.6.1"
      }
    },
    "react-proxy": {
      "version": "1.1.8",
      "resolved": "https://registry.npmjs.org/react-proxy/-/react-proxy-1.1.8.tgz",
      "integrity": "sha1-nb/Z2SdSjDqp9ETkVYw3gwq4wmo=",
      "requires": {
        "lodash": "^4.6.1",
        "react-deep-force-update": "^1.0.0"
      }
    },
    "react-timer-mixin": {
      "version": "0.13.4",
      "resolved": "https://registry.npmjs.org/react-timer-mixin/-/react-timer-mixin-0.13.4.tgz",
      "integrity": "sha512-4+ow23tp/Tv7hBM5Az5/Be/eKKF7DIvJ09voz5LyHGQaqqz9WV8YMs31eFvcYQs7d451LSg7kDJV70XYN/Ug/Q=="
    },
    "react-transform-hmr": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/react-transform-hmr/-/react-transform-hmr-1.0.4.tgz",
      "integrity": "sha1-4aQL0Krvxy6N/Xp82gmvhQZjl7s=",
      "requires": {
        "global": "^4.3.0",
        "react-proxy": "^1.1.7"
      }
    },
    "react-transition-group": {
      "version": "2.5.3",
      "resolved": "https://registry.npmjs.org/react-transition-group/-/react-transition-group-2.5.3.tgz",
      "integrity": "sha512-2DGFck6h99kLNr8pOFk+z4Soq3iISydwOFeeEVPjTN6+Y01CmvbWmnN02VuTWyFdnRtIDPe+wy2q6Ui8snBPZg==",
      "requires": {
        "dom-helpers": "^3.3.1",
        "loose-envify": "^1.4.0",
        "prop-types": "^15.6.2",
        "react-lifecycles-compat": "^3.0.4"
      }
    },
    "react-tween-state": {
      "version": "0.1.5",
      "resolved": "https://registry.npmjs.org/react-tween-state/-/react-tween-state-0.1.5.tgz",
      "integrity": "sha1-6YsGZVHvuTy5LdG+FJlcLj3q4zk=",
      "requires": {
        "raf": "^3.1.0",
        "tween-functions": "^1.0.1"
      }
    },
    "reactstrap": {
      "version": "7.1.0",
      "resolved": "https://registry.npmjs.org/reactstrap/-/reactstrap-7.1.0.tgz",
      "integrity": "sha512-wtc4RkgnGn1TsZ0AxOZ2OqT+b8YmCWZj/tErPujWLepxzlEEhveZGC+uDerdaHVSAzJUP2DTk605iper7hutQQ==",
      "requires": {
        "@babel/runtime": "^7.2.0",
        "classnames": "^2.2.3",
        "lodash.isfunction": "^3.0.9",
        "lodash.isobject": "^3.0.2",
        "lodash.tonumber": "^4.0.3",
        "prop-types": "^15.5.8",
        "react-lifecycles-compat": "^3.0.4",
        "react-popper": "^0.10.4",
        "react-transition-group": "^2.3.1"
      }
    },
    "read-pkg": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/read-pkg/-/read-pkg-2.0.0.tgz",
      "integrity": "sha1-jvHAYjxqbbDcZxPEv6xGMysjaPg=",
      "requires": {
        "load-json-file": "^2.0.0",
        "normalize-package-data": "^2.3.2",
        "path-type": "^2.0.0"
      }
    },
    "read-pkg-up": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/read-pkg-up/-/read-pkg-up-2.0.0.tgz",
      "integrity": "sha1-a3KoBImE4MQeeVEP1en6mbO1Sb4=",
      "requires": {
        "find-up": "^2.0.0",
        "read-pkg": "^2.0.0"
      }
    },
    "readable-stream": {
      "version": "2.3.6",
      "resolved": "https://registry.npmjs.org/readable-stream/-/readable-stream-2.3.6.tgz",
      "integrity": "sha512-tQtKA9WIAhBF3+VLAseyMqZeBjW0AHJoxOtYqSUZNJxauErmLbVm2FW1y+J/YA9dUrAC39ITejlZWhVIwawkKw==",
      "requires": {
        "core-util-is": "~1.0.0",
        "inherits": "~2.0.3",
        "isarray": "~1.0.0",
        "process-nextick-args": "~2.0.0",
        "safe-buffer": "~5.1.1",
        "string_decoder": "~1.1.1",
        "util-deprecate": "~1.0.1"
      }
    },
    "regenerate": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/regenerate/-/regenerate-1.4.0.tgz",
      "integrity": "sha512-1G6jJVDWrt0rK99kBjvEtziZNCICAuvIPkSiUFIQxVP06RCVpq3dmDo2oi6ABpYaDYaTRr67BEhL8r1wgEZZKg=="
    },
    "regenerate-unicode-properties": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/regenerate-unicode-properties/-/regenerate-unicode-properties-7.0.0.tgz",
      "integrity": "sha512-s5NGghCE4itSlUS+0WUj88G6cfMVMmH8boTPNvABf8od+2dhT9WDlWu8n01raQAJZMOK8Ch6jSexaRO7swd6aw==",
      "requires": {
        "regenerate": "^1.4.0"
      }
    },
    "regenerator-runtime": {
      "version": "0.11.1",
      "resolved": "https://registry.npmjs.org/regenerator-runtime/-/regenerator-runtime-0.11.1.tgz",
      "integrity": "sha512-MguG95oij0fC3QV3URf4V2SDYGJhJnJGqvIIgdECeODCT98wSWDAJ94SSuVpYQUoTcGUIL6L4yNB7j1DFFHSBg=="
    },
    "regenerator-transform": {
      "version": "0.13.3",
      "resolved": "https://registry.npmjs.org/regenerator-transform/-/regenerator-transform-0.13.3.tgz",
      "integrity": "sha512-5ipTrZFSq5vU2YoGoww4uaRVAK4wyYC4TSICibbfEPOruUu8FFP7ErV0BjmbIOEpn3O/k9na9UEdYR/3m7N6uA==",
      "requires": {
        "private": "^0.1.6"
      }
    },
    "regex-cache": {
      "version": "0.4.4",
      "resolved": "https://registry.npmjs.org/regex-cache/-/regex-cache-0.4.4.tgz",
      "integrity": "sha512-nVIZwtCjkC9YgvWkpM55B5rBhBYRZhAaJbgcFYXXsHnbZ9UZI9nnVWYZpBlCqv9ho2eZryPnWrZGsOdPwVWXWQ==",
      "requires": {
        "is-equal-shallow": "^0.1.3"
      }
    },
    "regex-not": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/regex-not/-/regex-not-1.0.2.tgz",
      "integrity": "sha512-J6SDjUgDxQj5NusnOtdFxDwN/+HWykR8GELwctJ7mdqhcyy1xEc4SRFHUXvxTp661YaVKAjfRLZ9cCqS6tn32A==",
      "requires": {
        "extend-shallow": "^3.0.2",
        "safe-regex": "^1.1.0"
      },
      "dependencies": {
        "extend-shallow": {
          "version": "3.0.2",
          "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-3.0.2.tgz",
          "integrity": "sha1-Jqcarwc7OfshJxcnRhMcJwQCjbg=",
          "requires": {
            "assign-symbols": "^1.0.0",
            "is-extendable": "^1.0.1"
          }
        },
        "is-extendable": {
          "version": "1.0.1",
          "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-1.0.1.tgz",
          "integrity": "sha512-arnXMxT1hhoKo9k1LZdmlNyJdDDfy2v0fXjFlmok4+i8ul/6WlbVge9bhM74OpNPQPMGUToDtz+KXa1PneJxOA==",
          "requires": {
            "is-plain-object": "^2.0.4"
          }
        }
      }
    },
    "regexpu-core": {
      "version": "4.4.0",
      "resolved": "https://registry.npmjs.org/regexpu-core/-/regexpu-core-4.4.0.tgz",
      "integrity": "sha512-eDDWElbwwI3K0Lo6CqbQbA6FwgtCz4kYTarrri1okfkRLZAqstU+B3voZBCjg8Fl6iq0gXrJG6MvRgLthfvgOA==",
      "requires": {
        "regenerate": "^1.4.0",
        "regenerate-unicode-properties": "^7.0.0",
        "regjsgen": "^0.5.0",
        "regjsparser": "^0.6.0",
        "unicode-match-property-ecmascript": "^1.0.4",
        "unicode-match-property-value-ecmascript": "^1.0.2"
      }
    },
    "regjsgen": {
      "version": "0.5.0",
      "resolved": "https://registry.npmjs.org/regjsgen/-/regjsgen-0.5.0.tgz",
      "integrity": "sha512-RnIrLhrXCX5ow/E5/Mh2O4e/oa1/jW0eaBKTSy3LaCj+M3Bqvm97GWDp2yUtzIs4LEn65zR2yiYGFqb2ApnzDA=="
    },
    "regjsparser": {
      "version": "0.6.0",
      "resolved": "https://registry.npmjs.org/regjsparser/-/regjsparser-0.6.0.tgz",
      "integrity": "sha512-RQ7YyokLiQBomUJuUG8iGVvkgOLxwyZM8k6d3q5SAXpg4r5TZJZigKFvC6PpD+qQ98bCDC5YelPeA3EucDoNeQ==",
      "requires": {
        "jsesc": "~0.5.0"
      },
      "dependencies": {
        "jsesc": {
          "version": "0.5.0",
          "resolved": "https://registry.npmjs.org/jsesc/-/jsesc-0.5.0.tgz",
          "integrity": "sha1-597mbjXW/Bb3EP6R1c9p9w8IkR0="
        }
      }
    },
    "remove-trailing-separator": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/remove-trailing-separator/-/remove-trailing-separator-1.1.0.tgz",
      "integrity": "sha1-wkvOKig62tW8P1jg1IJJuSN52O8="
    },
    "repeat-element": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/repeat-element/-/repeat-element-1.1.3.tgz",
      "integrity": "sha512-ahGq0ZnV5m5XtZLMb+vP76kcAM5nkLqk0lpqAuojSKGgQtn4eRi4ZZGm2olo2zKFH+sMsWaqOCW1dqAnOru72g=="
    },
    "repeat-string": {
      "version": "1.6.1",
      "resolved": "https://registry.npmjs.org/repeat-string/-/repeat-string-1.6.1.tgz",
      "integrity": "sha1-jcrkcOHIirwtYA//Sndihtp15jc="
    },
    "repeating": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/repeating/-/repeating-2.0.1.tgz",
      "integrity": "sha1-UhTFOpJtNVJwdSf7q0FdvAjQbdo=",
      "requires": {
        "is-finite": "^1.0.0"
      }
    },
    "require-directory": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/require-directory/-/require-directory-2.1.1.tgz",
      "integrity": "sha1-jGStX9MNqxyXbiNE/+f3kqam30I="
    },
    "require-main-filename": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/require-main-filename/-/require-main-filename-1.0.1.tgz",
      "integrity": "sha1-l/cXtp1IeE9fUmpsWqj/3aBVpNE="
    },
    "reselect": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/reselect/-/reselect-3.0.1.tgz",
      "integrity": "sha1-79qpjqdFEyTQkrKyFjpqHXqaIUc="
    },
    "resolve": {
      "version": "1.10.0",
      "resolved": "https://registry.npmjs.org/resolve/-/resolve-1.10.0.tgz",
      "integrity": "sha512-3sUr9aq5OfSg2S9pNtPA9hL1FVEAjvfOC4leW0SNf/mpnaakz2a9femSd6LqAww2RaFctwyf1lCqnTHuF1rxDg==",
      "requires": {
        "path-parse": "^1.0.6"
      }
    },
    "resolve-from": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/resolve-from/-/resolve-from-3.0.0.tgz",
      "integrity": "sha1-six699nWiBvItuZTM17rywoYh0g="
    },
    "resolve-url": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/resolve-url/-/resolve-url-0.2.1.tgz",
      "integrity": "sha1-LGN/53yJOv0qZj/iGqkIAGjiBSo="
    },
    "restore-cursor": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/restore-cursor/-/restore-cursor-2.0.0.tgz",
      "integrity": "sha1-n37ih/gv0ybU/RYpI9YhKe7g368=",
      "requires": {
        "onetime": "^2.0.0",
        "signal-exit": "^3.0.2"
      }
    },
    "ret": {
      "version": "0.1.15",
      "resolved": "https://registry.npmjs.org/ret/-/ret-0.1.15.tgz",
      "integrity": "sha512-TTlYpa+OL+vMMNG24xSlQGEJ3B/RzEfUlLct7b5G/ytav+wPrplCpVMFuwzXbkecJrb6IYo1iFb0S9v37754mg=="
    },
    "rimraf": {
      "version": "2.6.3",
      "resolved": "https://registry.npmjs.org/rimraf/-/rimraf-2.6.3.tgz",
      "integrity": "sha512-mwqeW5XsA2qAejG46gYdENaxXjx9onRNCfn7L0duuP4hCuTIi/QO7PDK07KJfp1d+izWPrzEJDcSqBa0OZQriA==",
      "requires": {
        "glob": "^7.1.3"
      }
    },
    "rsvp": {
      "version": "3.6.2",
      "resolved": "https://registry.npmjs.org/rsvp/-/rsvp-3.6.2.tgz",
      "integrity": "sha512-OfWGQTb9vnwRjwtA2QwpG2ICclHC3pgXZO5xt8H2EfgDquO0qVdSb5T88L4qJVAEugbS56pAuV4XZM58UX8ulw=="
    },
    "rtl-detect": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/rtl-detect/-/rtl-detect-1.0.2.tgz",
      "integrity": "sha512-5X1422hvphzg2a/bo4tIDbjFjbJUOaPZwqE6dnyyxqwFqfR+tBcvfqapJr0o0VygATVCGKiODEewhZtKF+90AA=="
    },
    "run-async": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/run-async/-/run-async-2.3.0.tgz",
      "integrity": "sha1-A3GrSuC91yDUFm19/aZP96RFpsA=",
      "requires": {
        "is-promise": "^2.1.0"
      }
    },
    "rx-lite": {
      "version": "4.0.8",
      "resolved": "https://registry.npmjs.org/rx-lite/-/rx-lite-4.0.8.tgz",
      "integrity": "sha1-Cx4Rr4vESDbwSmQH6S2kJGe3lEQ="
    },
    "rx-lite-aggregates": {
      "version": "4.0.8",
      "resolved": "https://registry.npmjs.org/rx-lite-aggregates/-/rx-lite-aggregates-4.0.8.tgz",
      "integrity": "sha1-dTuHqJoRyVRnxKwWJsTvxOBcZ74=",
      "requires": {
        "rx-lite": "*"
      }
    },
    "safe-buffer": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/safe-buffer/-/safe-buffer-5.1.2.tgz",
      "integrity": "sha512-Gd2UZBJDkXlY7GbJxfsE8/nvKkUEU1G38c1siN6QP6a9PT9MmHB8GnpscSmMJSoF8LOIrt8ud/wPtojys4G6+g=="
    },
    "safe-regex": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/safe-regex/-/safe-regex-1.1.0.tgz",
      "integrity": "sha1-QKNmnzsHfR6UPURinhV91IAjvy4=",
      "requires": {
        "ret": "~0.1.10"
      }
    },
    "safer-buffer": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/safer-buffer/-/safer-buffer-2.1.2.tgz",
      "integrity": "sha512-YZo3K82SD7Riyi0E1EQPojLz7kpepnSQI9IyPbHHg1XXXevb5dJI7tpyN2ADxGcQbHG7vcyRHk0cbwqcQriUtg=="
    },
    "sane": {
      "version": "2.5.2",
      "resolved": "https://registry.npmjs.org/sane/-/sane-2.5.2.tgz",
      "integrity": "sha1-tNwYYcIbQn6SlQej51HiosuKs/o=",
      "requires": {
        "anymatch": "^2.0.0",
        "capture-exit": "^1.2.0",
        "exec-sh": "^0.2.0",
        "fb-watchman": "^2.0.0",
        "fsevents": "^1.2.3",
        "micromatch": "^3.1.4",
        "minimist": "^1.1.1",
        "walker": "~1.0.5",
        "watch": "~0.18.0"
      },
      "dependencies": {
        "arr-diff": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/arr-diff/-/arr-diff-4.0.0.tgz",
          "integrity": "sha1-1kYQdP6/7HHn4VI1dhoyml3HxSA="
        },
        "array-unique": {
          "version": "0.3.2",
          "resolved": "https://registry.npmjs.org/array-unique/-/array-unique-0.3.2.tgz",
          "integrity": "sha1-qJS3XUvE9s1nnvMkSp/Y9Gri1Cg="
        },
        "braces": {
          "version": "2.3.2",
          "resolved": "https://registry.npmjs.org/braces/-/braces-2.3.2.tgz",
          "integrity": "sha512-aNdbnj9P8PjdXU4ybaWLK2IF3jc/EoDYbC7AazW6to3TRsfXxscC9UXOB5iDiEQrkyIbWp2SLQda4+QAa7nc3w==",
          "requires": {
            "arr-flatten": "^1.1.0",
            "array-unique": "^0.3.2",
            "extend-shallow": "^2.0.1",
            "fill-range": "^4.0.0",
            "isobject": "^3.0.1",
            "repeat-element": "^1.1.2",
            "snapdragon": "^0.8.1",
            "snapdragon-node": "^2.0.1",
            "split-string": "^3.0.2",
            "to-regex": "^3.0.1"
          },
          "dependencies": {
            "extend-shallow": {
              "version": "2.0.1",
              "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
              "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
              "requires": {
                "is-extendable": "^0.1.0"
              }
            }
          }
        },
        "expand-brackets": {
          "version": "2.1.4",
          "resolved": "https://registry.npmjs.org/expand-brackets/-/expand-brackets-2.1.4.tgz",
          "integrity": "sha1-t3c14xXOMPa27/D4OwQVGiJEliI=",
          "requires": {
            "debug": "^2.3.3",
            "define-property": "^0.2.5",
            "extend-shallow": "^2.0.1",
            "posix-character-classes": "^0.1.0",
            "regex-not": "^1.0.0",
            "snapdragon": "^0.8.1",
            "to-regex": "^3.0.1"
          },
          "dependencies": {
            "define-property": {
              "version": "0.2.5",
              "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
              "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
              "requires": {
                "is-descriptor": "^0.1.0"
              }
            },
            "extend-shallow": {
              "version": "2.0.1",
              "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
              "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
              "requires": {
                "is-extendable": "^0.1.0"
              }
            },
            "is-accessor-descriptor": {
              "version": "0.1.6",
              "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-0.1.6.tgz",
              "integrity": "sha1-qeEss66Nh2cn7u84Q/igiXtcmNY=",
              "requires": {
                "kind-of": "^3.0.2"
              },
              "dependencies": {
                "kind-of": {
                  "version": "3.2.2",
                  "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
                  "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
                  "requires": {
                    "is-buffer": "^1.1.5"
                  }
                }
              }
            },
            "is-data-descriptor": {
              "version": "0.1.4",
              "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-0.1.4.tgz",
              "integrity": "sha1-C17mSDiOLIYCgueT8YVv7D8wG1Y=",
              "requires": {
                "kind-of": "^3.0.2"
              },
              "dependencies": {
                "kind-of": {
                  "version": "3.2.2",
                  "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
                  "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
                  "requires": {
                    "is-buffer": "^1.1.5"
                  }
                }
              }
            },
            "is-descriptor": {
              "version": "0.1.6",
              "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-0.1.6.tgz",
              "integrity": "sha512-avDYr0SB3DwO9zsMov0gKCESFYqCnE4hq/4z3TdUlukEy5t9C0YRq7HLrsN52NAcqXKaepeCD0n+B0arnVG3Hg==",
              "requires": {
                "is-accessor-descriptor": "^0.1.6",
                "is-data-descriptor": "^0.1.4",
                "kind-of": "^5.0.0"
              }
            },
            "kind-of": {
              "version": "5.1.0",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-5.1.0.tgz",
              "integrity": "sha512-NGEErnH6F2vUuXDh+OlbcKW7/wOcfdRHaZ7VWtqCztfHri/++YKmP51OdWeGPuqCOba6kk2OTe5d02VmTB80Pw=="
            }
          }
        },
        "extend-shallow": {
          "version": "3.0.2",
          "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-3.0.2.tgz",
          "integrity": "sha1-Jqcarwc7OfshJxcnRhMcJwQCjbg=",
          "requires": {
            "assign-symbols": "^1.0.0",
            "is-extendable": "^1.0.1"
          },
          "dependencies": {
            "is-extendable": {
              "version": "1.0.1",
              "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-1.0.1.tgz",
              "integrity": "sha512-arnXMxT1hhoKo9k1LZdmlNyJdDDfy2v0fXjFlmok4+i8ul/6WlbVge9bhM74OpNPQPMGUToDtz+KXa1PneJxOA==",
              "requires": {
                "is-plain-object": "^2.0.4"
              }
            }
          }
        },
        "extglob": {
          "version": "2.0.4",
          "resolved": "https://registry.npmjs.org/extglob/-/extglob-2.0.4.tgz",
          "integrity": "sha512-Nmb6QXkELsuBr24CJSkilo6UHHgbekK5UiZgfE6UHD3Eb27YC6oD+bhcT+tJ6cl8dmsgdQxnWlcry8ksBIBLpw==",
          "requires": {
            "array-unique": "^0.3.2",
            "define-property": "^1.0.0",
            "expand-brackets": "^2.1.4",
            "extend-shallow": "^2.0.1",
            "fragment-cache": "^0.2.1",
            "regex-not": "^1.0.0",
            "snapdragon": "^0.8.1",
            "to-regex": "^3.0.1"
          },
          "dependencies": {
            "define-property": {
              "version": "1.0.0",
              "resolved": "https://registry.npmjs.org/define-property/-/define-property-1.0.0.tgz",
              "integrity": "sha1-dp66rz9KY6rTr56NMEybvnm/sOY=",
              "requires": {
                "is-descriptor": "^1.0.0"
              }
            },
            "extend-shallow": {
              "version": "2.0.1",
              "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
              "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
              "requires": {
                "is-extendable": "^0.1.0"
              }
            }
          }
        },
        "fill-range": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/fill-range/-/fill-range-4.0.0.tgz",
          "integrity": "sha1-1USBHUKPmOsGpj3EAtJAPDKMOPc=",
          "requires": {
            "extend-shallow": "^2.0.1",
            "is-number": "^3.0.0",
            "repeat-string": "^1.6.1",
            "to-regex-range": "^2.1.0"
          },
          "dependencies": {
            "extend-shallow": {
              "version": "2.0.1",
              "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
              "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
              "requires": {
                "is-extendable": "^0.1.0"
              }
            }
          }
        },
        "is-accessor-descriptor": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-1.0.0.tgz",
          "integrity": "sha512-m5hnHTkcVsPfqx3AKlyttIPb7J+XykHvJP2B9bZDjlhLIoEq4XoK64Vg7boZlVWYK6LUY94dYPEE7Lh0ZkZKcQ==",
          "requires": {
            "kind-of": "^6.0.0"
          }
        },
        "is-data-descriptor": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-1.0.0.tgz",
          "integrity": "sha512-jbRXy1FmtAoCjQkVmIVYwuuqDFUbaOeDjmed1tOGPrsMhtJA4rD9tkgA0F1qJ3gRFRXcHYVkdeaP50Q5rE/jLQ==",
          "requires": {
            "kind-of": "^6.0.0"
          }
        },
        "is-descriptor": {
          "version": "1.0.2",
          "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-1.0.2.tgz",
          "integrity": "sha512-2eis5WqQGV7peooDyLmNEPUrps9+SXX5c9pL3xEB+4e9HnGuDa7mB7kHxHw4CbqS9k1T2hOH3miL8n8WtiYVtg==",
          "requires": {
            "is-accessor-descriptor": "^1.0.0",
            "is-data-descriptor": "^1.0.0",
            "kind-of": "^6.0.2"
          }
        },
        "is-number": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/is-number/-/is-number-3.0.0.tgz",
          "integrity": "sha1-JP1iAaR4LPUFYcgQJ2r8fRLXEZU=",
          "requires": {
            "kind-of": "^3.0.2"
          },
          "dependencies": {
            "kind-of": {
              "version": "3.2.2",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
              "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
              "requires": {
                "is-buffer": "^1.1.5"
              }
            }
          }
        },
        "isobject": {
          "version": "3.0.1",
          "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
          "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8="
        },
        "kind-of": {
          "version": "6.0.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-6.0.2.tgz",
          "integrity": "sha512-s5kLOcnH0XqDO+FvuaLX8DDjZ18CGFk7VygH40QoKPUQhW4e2rvM0rwUq0t8IQDOwYSeLK01U90OjzBTme2QqA=="
        },
        "micromatch": {
          "version": "3.1.10",
          "resolved": "https://registry.npmjs.org/micromatch/-/micromatch-3.1.10.tgz",
          "integrity": "sha512-MWikgl9n9M3w+bpsY3He8L+w9eF9338xRl8IAO5viDizwSzziFEyUzo2xrrloB64ADbTf8uA8vRqqttDTOmccg==",
          "requires": {
            "arr-diff": "^4.0.0",
            "array-unique": "^0.3.2",
            "braces": "^2.3.1",
            "define-property": "^2.0.2",
            "extend-shallow": "^3.0.2",
            "extglob": "^2.0.4",
            "fragment-cache": "^0.2.1",
            "kind-of": "^6.0.2",
            "nanomatch": "^1.2.9",
            "object.pick": "^1.3.0",
            "regex-not": "^1.0.0",
            "snapdragon": "^0.8.1",
            "to-regex": "^3.0.2"
          }
        }
      }
    },
    "sax": {
      "version": "1.1.6",
      "resolved": "https://registry.npmjs.org/sax/-/sax-1.1.6.tgz",
      "integrity": "sha1-XWFr6KXmB9VOEUr65Vt+ry/MMkA="
    },
    "schedule": {
      "version": "0.3.0",
      "resolved": "https://registry.npmjs.org/schedule/-/schedule-0.3.0.tgz",
      "integrity": "sha512-20+1KVo517sR7Nt+bYBN8a+bEJDKLPEx7Ohtts1kX05E4/HY53YUNuhfkVNItmWAnBYHcpG9vsd2/CJxG+aPCQ==",
      "requires": {
        "object-assign": "^4.1.1"
      }
    },
    "schema-utils": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/schema-utils/-/schema-utils-1.0.0.tgz",
      "integrity": "sha512-i27Mic4KovM/lnGsy8whRCHhc7VicJajAjTrYg11K9zfZXnYIt4k5F+kZkwjnrhKzLic/HLU4j11mjsz2G/75g==",
      "requires": {
        "ajv": "^6.1.0",
        "ajv-errors": "^1.0.0",
        "ajv-keywords": "^3.1.0"
      }
    },
    "semver": {
      "version": "5.6.0",
      "resolved": "https://registry.npmjs.org/semver/-/semver-5.6.0.tgz",
      "integrity": "sha512-RS9R6R35NYgQn++fkDWaOmqGoj4Ek9gGs+DPxNUZKuwE183xjJroKvyo1IzVFeXvUrvmALy6FWD5xrdJT25gMg=="
    },
    "send": {
      "version": "0.16.2",
      "resolved": "https://registry.npmjs.org/send/-/send-0.16.2.tgz",
      "integrity": "sha512-E64YFPUssFHEFBvpbbjr44NCLtI1AohxQ8ZSiJjQLskAdKuriYEP6VyGEsRDH8ScozGpkaX1BGvhanqCwkcEZw==",
      "requires": {
        "debug": "2.6.9",
        "depd": "~1.1.2",
        "destroy": "~1.0.4",
        "encodeurl": "~1.0.2",
        "escape-html": "~1.0.3",
        "etag": "~1.8.1",
        "fresh": "0.5.2",
        "http-errors": "~1.6.2",
        "mime": "1.4.1",
        "ms": "2.0.0",
        "on-finished": "~2.3.0",
        "range-parser": "~1.2.0",
        "statuses": "~1.4.0"
      },
      "dependencies": {
        "mime": {
          "version": "1.4.1",
          "resolved": "https://registry.npmjs.org/mime/-/mime-1.4.1.tgz",
          "integrity": "sha512-KI1+qOZu5DcW6wayYHSzR/tXKCDC5Om4s1z2QJjDULzLcmf3DvzS7oluY4HCTrc+9FiKmWUgeNLg7W3uIQvxtQ=="
        },
        "statuses": {
          "version": "1.4.0",
          "resolved": "https://registry.npmjs.org/statuses/-/statuses-1.4.0.tgz",
          "integrity": "sha512-zhSCtt8v2NDrRlPQpCNtw/heZLtfUDqxBM1udqikb/Hbk52LK4nQSwr10u77iopCW5LsyHpuXS0GnEc48mLeew=="
        }
      }
    },
    "serialize-error": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/serialize-error/-/serialize-error-2.1.0.tgz",
      "integrity": "sha1-ULZ51WNc34Rme9yOWa9OW4HV9go="
    },
    "serve-static": {
      "version": "1.13.2",
      "resolved": "https://registry.npmjs.org/serve-static/-/serve-static-1.13.2.tgz",
      "integrity": "sha512-p/tdJrO4U387R9oMjb1oj7qSMaMfmOyd4j9hOFoxZe2baQszgHcSWjuya/CiT5kgZZKRudHNOA0pYXOl8rQ5nw==",
      "requires": {
        "encodeurl": "~1.0.2",
        "escape-html": "~1.0.3",
        "parseurl": "~1.3.2",
        "send": "0.16.2"
      }
    },
    "set-blocking": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/set-blocking/-/set-blocking-2.0.0.tgz",
      "integrity": "sha1-BF+XgtARrppoA93TgrJDkrPYkPc="
    },
    "set-value": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/set-value/-/set-value-2.0.0.tgz",
      "integrity": "sha512-hw0yxk9GT/Hr5yJEYnHNKYXkIA8mVJgd9ditYZCe16ZczcaELYYcfvaXesNACk2O8O0nTiPQcQhGUQj8JLzeeg==",
      "requires": {
        "extend-shallow": "^2.0.1",
        "is-extendable": "^0.1.1",
        "is-plain-object": "^2.0.3",
        "split-string": "^3.0.1"
      },
      "dependencies": {
        "extend-shallow": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
          "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
          "requires": {
            "is-extendable": "^0.1.0"
          }
        }
      }
    },
    "setimmediate": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/setimmediate/-/setimmediate-1.0.5.tgz",
      "integrity": "sha1-KQy7Iy4waULX1+qbg3Mqt4VvgoU="
    },
    "setprototypeof": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/setprototypeof/-/setprototypeof-1.1.0.tgz",
      "integrity": "sha512-BvE/TwpZX4FXExxOxZyRGQQv651MSwmWKZGqvmPcRIjDqWub67kTKuIMx43cZZrS/cBBzwBcNDWoFxt2XEFIpQ=="
    },
    "shebang-command": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/shebang-command/-/shebang-command-1.2.0.tgz",
      "integrity": "sha1-RKrGW2lbAzmJaMOfNj/uXer98eo=",
      "requires": {
        "shebang-regex": "^1.0.0"
      }
    },
    "shebang-regex": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/shebang-regex/-/shebang-regex-1.0.0.tgz",
      "integrity": "sha1-2kL0l0DAtC2yypcoVxyxkMmO/qM="
    },
    "shell-quote": {
      "version": "1.6.1",
      "resolved": "https://registry.npmjs.org/shell-quote/-/shell-quote-1.6.1.tgz",
      "integrity": "sha1-9HgZSczkAmlxJ0MOo7PFR29IF2c=",
      "requires": {
        "array-filter": "~0.0.0",
        "array-map": "~0.0.0",
        "array-reduce": "~0.0.0",
        "jsonify": "~0.0.0"
      }
    },
    "shellwords": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/shellwords/-/shellwords-0.1.1.tgz",
      "integrity": "sha512-vFwSUfQvqybiICwZY5+DAWIPLKsWO31Q91JSKl3UYv+K5c2QRPzn0qzec6QPu1Qc9eHYItiP3NdJqNVqetYAww=="
    },
    "signal-exit": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/signal-exit/-/signal-exit-3.0.2.tgz",
      "integrity": "sha1-tf3AjxKH6hF4Yo5BXiUTK3NkbG0="
    },
    "simple-plist": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/simple-plist/-/simple-plist-0.2.1.tgz",
      "integrity": "sha1-cXZts1IyaSjPOoByQrp2IyJjZyM=",
      "requires": {
        "bplist-creator": "0.0.7",
        "bplist-parser": "0.1.1",
        "plist": "2.0.1"
      },
      "dependencies": {
        "base64-js": {
          "version": "1.1.2",
          "resolved": "https://registry.npmjs.org/base64-js/-/base64-js-1.1.2.tgz",
          "integrity": "sha1-1kAMrBxMZgl22Q0HoENR2JOV9eg="
        },
        "plist": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/plist/-/plist-2.0.1.tgz",
          "integrity": "sha1-CjLKlIGxw2TpLhjcVch23p0B2os=",
          "requires": {
            "base64-js": "1.1.2",
            "xmlbuilder": "8.2.2",
            "xmldom": "0.1.x"
          }
        },
        "xmlbuilder": {
          "version": "8.2.2",
          "resolved": "https://registry.npmjs.org/xmlbuilder/-/xmlbuilder-8.2.2.tgz",
          "integrity": "sha1-aSSGc0ELS6QuGmE2VR0pIjNap3M="
        }
      }
    },
    "simple-swizzle": {
      "version": "0.2.2",
      "resolved": "https://registry.npmjs.org/simple-swizzle/-/simple-swizzle-0.2.2.tgz",
      "integrity": "sha1-pNprY1/8zMoz9w0Xy5JZLeleVXo=",
      "requires": {
        "is-arrayish": "^0.3.1"
      }
    },
    "slash": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/slash/-/slash-1.0.0.tgz",
      "integrity": "sha1-xB8vbDn8FtHNF61LXYlhFK5HDVU="
    },
    "slide": {
      "version": "1.1.6",
      "resolved": "https://registry.npmjs.org/slide/-/slide-1.1.6.tgz",
      "integrity": "sha1-VusCfWW00tzmyy4tMsTUr8nh1wc="
    },
    "snapdragon": {
      "version": "0.8.2",
      "resolved": "https://registry.npmjs.org/snapdragon/-/snapdragon-0.8.2.tgz",
      "integrity": "sha512-FtyOnWN/wCHTVXOMwvSv26d+ko5vWlIDD6zoUJ7LW8vh+ZBC8QdljveRP+crNrtBwioEUWy/4dMtbBjA4ioNlg==",
      "requires": {
        "base": "^0.11.1",
        "debug": "^2.2.0",
        "define-property": "^0.2.5",
        "extend-shallow": "^2.0.1",
        "map-cache": "^0.2.2",
        "source-map": "^0.5.6",
        "source-map-resolve": "^0.5.0",
        "use": "^3.1.0"
      },
      "dependencies": {
        "define-property": {
          "version": "0.2.5",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
          "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
          "requires": {
            "is-descriptor": "^0.1.0"
          }
        },
        "extend-shallow": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
          "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
          "requires": {
            "is-extendable": "^0.1.0"
          }
        }
      }
    },
    "snapdragon-node": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/snapdragon-node/-/snapdragon-node-2.1.1.tgz",
      "integrity": "sha512-O27l4xaMYt/RSQ5TR3vpWCAB5Kb/czIcqUFOM/C4fYcLnbZUc1PkjTAMjof2pBWaSTwOUd6qUHcFGVGj7aIwnw==",
      "requires": {
        "define-property": "^1.0.0",
        "isobject": "^3.0.0",
        "snapdragon-util": "^3.0.1"
      },
      "dependencies": {
        "define-property": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-1.0.0.tgz",
          "integrity": "sha1-dp66rz9KY6rTr56NMEybvnm/sOY=",
          "requires": {
            "is-descriptor": "^1.0.0"
          }
        },
        "is-accessor-descriptor": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-1.0.0.tgz",
          "integrity": "sha512-m5hnHTkcVsPfqx3AKlyttIPb7J+XykHvJP2B9bZDjlhLIoEq4XoK64Vg7boZlVWYK6LUY94dYPEE7Lh0ZkZKcQ==",
          "requires": {
            "kind-of": "^6.0.0"
          }
        },
        "is-data-descriptor": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-1.0.0.tgz",
          "integrity": "sha512-jbRXy1FmtAoCjQkVmIVYwuuqDFUbaOeDjmed1tOGPrsMhtJA4rD9tkgA0F1qJ3gRFRXcHYVkdeaP50Q5rE/jLQ==",
          "requires": {
            "kind-of": "^6.0.0"
          }
        },
        "is-descriptor": {
          "version": "1.0.2",
          "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-1.0.2.tgz",
          "integrity": "sha512-2eis5WqQGV7peooDyLmNEPUrps9+SXX5c9pL3xEB+4e9HnGuDa7mB7kHxHw4CbqS9k1T2hOH3miL8n8WtiYVtg==",
          "requires": {
            "is-accessor-descriptor": "^1.0.0",
            "is-data-descriptor": "^1.0.0",
            "kind-of": "^6.0.2"
          }
        },
        "isobject": {
          "version": "3.0.1",
          "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
          "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8="
        },
        "kind-of": {
          "version": "6.0.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-6.0.2.tgz",
          "integrity": "sha512-s5kLOcnH0XqDO+FvuaLX8DDjZ18CGFk7VygH40QoKPUQhW4e2rvM0rwUq0t8IQDOwYSeLK01U90OjzBTme2QqA=="
        }
      }
    },
    "snapdragon-util": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/snapdragon-util/-/snapdragon-util-3.0.1.tgz",
      "integrity": "sha512-mbKkMdQKsjX4BAL4bRYTj21edOf8cN7XHdYUJEe+Zn99hVEYcMvKPct1IqNe7+AZPirn8BCDOQBHQZknqmKlZQ==",
      "requires": {
        "kind-of": "^3.2.0"
      },
      "dependencies": {
        "kind-of": {
          "version": "3.2.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
          "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
          "requires": {
            "is-buffer": "^1.1.5"
          }
        }
      }
    },
    "source-map": {
      "version": "0.5.7",
      "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.5.7.tgz",
      "integrity": "sha1-igOdLRAh0i0eoUyA2OpGi6LvP8w="
    },
    "source-map-resolve": {
      "version": "0.5.2",
      "resolved": "https://registry.npmjs.org/source-map-resolve/-/source-map-resolve-0.5.2.tgz",
      "integrity": "sha512-MjqsvNwyz1s0k81Goz/9vRBe9SZdB09Bdw+/zYyO+3CuPk6fouTaxscHkgtE8jKvf01kVfl8riHzERQ/kefaSA==",
      "requires": {
        "atob": "^2.1.1",
        "decode-uri-component": "^0.2.0",
        "resolve-url": "^0.2.1",
        "source-map-url": "^0.4.0",
        "urix": "^0.1.0"
      }
    },
    "source-map-support": {
      "version": "0.4.18",
      "resolved": "https://registry.npmjs.org/source-map-support/-/source-map-support-0.4.18.tgz",
      "integrity": "sha512-try0/JqxPLF9nOjvSta7tVondkP5dwgyLDjVoyMDlmjugT2lRZ1OfsrYTkCd2hkDnJTKRbO/Rl3orm8vlsUzbA==",
      "requires": {
        "source-map": "^0.5.6"
      }
    },
    "source-map-url": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/source-map-url/-/source-map-url-0.4.0.tgz",
      "integrity": "sha1-PpNdfd1zYxuXZZlW1VEo6HtQhKM="
    },
    "spdx-correct": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/spdx-correct/-/spdx-correct-3.1.0.tgz",
      "integrity": "sha512-lr2EZCctC2BNR7j7WzJ2FpDznxky1sjfxvvYEyzxNyb6lZXHODmEoJeFu4JupYlkfha1KZpJyoqiJ7pgA1qq8Q==",
      "requires": {
        "spdx-expression-parse": "^3.0.0",
        "spdx-license-ids": "^3.0.0"
      }
    },
    "spdx-exceptions": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/spdx-exceptions/-/spdx-exceptions-2.2.0.tgz",
      "integrity": "sha512-2XQACfElKi9SlVb1CYadKDXvoajPgBVPn/gOQLrTvHdElaVhr7ZEbqJaRnJLVNeaI4cMEAgVCeBMKF6MWRDCRA=="
    },
    "spdx-expression-parse": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/spdx-expression-parse/-/spdx-expression-parse-3.0.0.tgz",
      "integrity": "sha512-Yg6D3XpRD4kkOmTpdgbUiEJFKghJH03fiC1OPll5h/0sO6neh2jqRDVHOQ4o/LMea0tgCkbMgea5ip/e+MkWyg==",
      "requires": {
        "spdx-exceptions": "^2.1.0",
        "spdx-license-ids": "^3.0.0"
      }
    },
    "spdx-license-ids": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/spdx-license-ids/-/spdx-license-ids-3.0.3.tgz",
      "integrity": "sha512-uBIcIl3Ih6Phe3XHK1NqboJLdGfwr1UN3k6wSD1dZpmPsIkb8AGNbZYJ1fOBk834+Gxy8rpfDxrS6XLEMZMY2g=="
    },
    "split-string": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/split-string/-/split-string-3.1.0.tgz",
      "integrity": "sha512-NzNVhJDYpwceVVii8/Hu6DKfD2G+NrQHlS/V/qgv763EYudVwEcMQNxd2lh+0VrUByXN/oJkl5grOhYWvQUYiw==",
      "requires": {
        "extend-shallow": "^3.0.0"
      },
      "dependencies": {
        "extend-shallow": {
          "version": "3.0.2",
          "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-3.0.2.tgz",
          "integrity": "sha1-Jqcarwc7OfshJxcnRhMcJwQCjbg=",
          "requires": {
            "assign-symbols": "^1.0.0",
            "is-extendable": "^1.0.1"
          }
        },
        "is-extendable": {
          "version": "1.0.1",
          "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-1.0.1.tgz",
          "integrity": "sha512-arnXMxT1hhoKo9k1LZdmlNyJdDDfy2v0fXjFlmok4+i8ul/6WlbVge9bhM74OpNPQPMGUToDtz+KXa1PneJxOA==",
          "requires": {
            "is-plain-object": "^2.0.4"
          }
        }
      }
    },
    "sprintf-js": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/sprintf-js/-/sprintf-js-1.0.3.tgz",
      "integrity": "sha1-BOaSb2YolTVPPdAVIDYzuFcpfiw="
    },
    "stacktrace-parser": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/stacktrace-parser/-/stacktrace-parser-0.1.4.tgz",
      "integrity": "sha1-ATl5IuX2Ls8whFUiyVxP4dJefU4="
    },
    "static-extend": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/static-extend/-/static-extend-0.1.2.tgz",
      "integrity": "sha1-YICcOcv/VTNyJv1eC1IPNB8ftcY=",
      "requires": {
        "define-property": "^0.2.5",
        "object-copy": "^0.1.0"
      },
      "dependencies": {
        "define-property": {
          "version": "0.2.5",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
          "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
          "requires": {
            "is-descriptor": "^0.1.0"
          }
        }
      }
    },
    "statuses": {
      "version": "1.3.1",
      "resolved": "https://registry.npmjs.org/statuses/-/statuses-1.3.1.tgz",
      "integrity": "sha1-+vUbnrdKrvOzrPStX2Gr8ky3uT4="
    },
    "stream-buffers": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/stream-buffers/-/stream-buffers-2.2.0.tgz",
      "integrity": "sha1-kdX1Ew0c75bc+n9yaUUYh0HQnuQ="
    },
    "strict-uri-encode": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/strict-uri-encode/-/strict-uri-encode-2.0.0.tgz",
      "integrity": "sha1-ucczDHBChi9rFC3CdLvMWGbONUY="
    },
    "string-width": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-2.1.1.tgz",
      "integrity": "sha512-nOqH59deCq9SRHlxq1Aw85Jnt4w6KvLKqWVik6oA9ZklXLNIOlqg4F2yrT1MVaTjAqvVwdfeZ7w7aCvJD7ugkw==",
      "requires": {
        "is-fullwidth-code-point": "^2.0.0",
        "strip-ansi": "^4.0.0"
      },
      "dependencies": {
        "ansi-regex": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-3.0.0.tgz",
          "integrity": "sha1-7QMXwyIGT3lGbAKWa922Bas32Zg="
        },
        "is-fullwidth-code-point": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/is-fullwidth-code-point/-/is-fullwidth-code-point-2.0.0.tgz",
          "integrity": "sha1-o7MKXE8ZkYMWeqq5O+764937ZU8="
        },
        "strip-ansi": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-4.0.0.tgz",
          "integrity": "sha1-qEeQIusaw2iocTibY1JixQXuNo8=",
          "requires": {
            "ansi-regex": "^3.0.0"
          }
        }
      }
    },
    "string_decoder": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/string_decoder/-/string_decoder-1.1.1.tgz",
      "integrity": "sha512-n/ShnvDi6FHbbVfviro+WojiFzv+s8MPMHBczVePfUpDJLwoLT0ht1l4YwBCbi8pJAveEEdnkHyPyTP/mzRfwg==",
      "requires": {
        "safe-buffer": "~5.1.0"
      }
    },
    "strip-ansi": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-3.0.1.tgz",
      "integrity": "sha1-ajhfuIU9lS1f8F0Oiq+UJ43GPc8=",
      "requires": {
        "ansi-regex": "^2.0.0"
      }
    },
    "strip-bom": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/strip-bom/-/strip-bom-3.0.0.tgz",
      "integrity": "sha1-IzTBjpx1n3vdVv3vfprj1YjmjtM="
    },
    "strip-eof": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/strip-eof/-/strip-eof-1.0.0.tgz",
      "integrity": "sha1-u0P/VZim6wXYm1n80SnJgzE2Br8="
    },
    "supports-color": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-2.0.0.tgz",
      "integrity": "sha1-U10EXOa2Nj+kARcIRimZXp3zJMc="
    },
    "symbol-observable": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/symbol-observable/-/symbol-observable-1.2.0.tgz",
      "integrity": "sha512-e900nM8RRtGhlV36KGEU9k65K3mPb1WV70OdjfxlG2EAuM1noi/E/BaW/uMhL7bPEssK8QV57vN3esixjUvcXQ=="
    },
    "synchronous-promise": {
      "version": "2.0.6",
      "resolved": "https://registry.npmjs.org/synchronous-promise/-/synchronous-promise-2.0.6.tgz",
      "integrity": "sha512-TyOuWLwkmtPL49LHCX1caIwHjRzcVd62+GF6h8W/jHOeZUFHpnd2XJDVuUlaTaLPH1nuu2M69mfHr5XbQJnf/g=="
    },
    "temp": {
      "version": "0.8.3",
      "resolved": "https://registry.npmjs.org/temp/-/temp-0.8.3.tgz",
      "integrity": "sha1-4Ma8TSa5AxJEEOT+2BEDAU38H1k=",
      "requires": {
        "os-tmpdir": "^1.0.0",
        "rimraf": "~2.2.6"
      },
      "dependencies": {
        "rimraf": {
          "version": "2.2.8",
          "resolved": "https://registry.npmjs.org/rimraf/-/rimraf-2.2.8.tgz",
          "integrity": "sha1-5Dm+Kq7jJzIZUnMPmaiSnk/FBYI="
        }
      }
    },
    "throat": {
      "version": "4.1.0",
      "resolved": "https://registry.npmjs.org/throat/-/throat-4.1.0.tgz",
      "integrity": "sha1-iQN8vJLFarGJJua6TLsgDhVnKmo="
    },
    "through": {
      "version": "2.3.8",
      "resolved": "https://registry.npmjs.org/through/-/through-2.3.8.tgz",
      "integrity": "sha1-DdTJ/6q8NXlgsbckEV1+Doai4fU="
    },
    "through2": {
      "version": "2.0.5",
      "resolved": "https://registry.npmjs.org/through2/-/through2-2.0.5.tgz",
      "integrity": "sha512-/mrRod8xqpA+IHSLyGCQ2s8SPHiCDEeQJSep1jqLYeEUClOFG2Qsh+4FU6G9VeqpZnGW/Su8LQGc4YKni5rYSQ==",
      "requires": {
        "readable-stream": "~2.3.6",
        "xtend": "~4.0.1"
      }
    },
    "time-stamp": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/time-stamp/-/time-stamp-1.1.0.tgz",
      "integrity": "sha1-dkpaEa9QVhkhsTPztE5hhofg9cM="
    },
    "tiny-queue": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/tiny-queue/-/tiny-queue-0.2.1.tgz",
      "integrity": "sha1-JaZ/LG4lOyypQZd7XvdELvl6YEY="
    },
    "tiny-warning": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/tiny-warning/-/tiny-warning-1.0.2.tgz",
      "integrity": "sha512-rru86D9CpQRLvsFG5XFdy0KdLAvjdQDyZCsRcuu60WtzFylDM3eAWSxEVz5kzL2Gp544XiUvPbVKtOA/txLi9Q=="
    },
    "tmp": {
      "version": "0.0.33",
      "resolved": "https://registry.npmjs.org/tmp/-/tmp-0.0.33.tgz",
      "integrity": "sha512-jRCJlojKnZ3addtTOjdIqoRuPEKBvNXcGYqzO6zWZX8KfKEpnGY5jfggJQ3EjKuu8D4bJRr0y+cYJFmYbImXGw==",
      "requires": {
        "os-tmpdir": "~1.0.2"
      }
    },
    "tmpl": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/tmpl/-/tmpl-1.0.4.tgz",
      "integrity": "sha1-I2QN17QtAEM5ERQIIOXPRA5SHdE="
    },
    "to-fast-properties": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/to-fast-properties/-/to-fast-properties-2.0.0.tgz",
      "integrity": "sha1-3F5pjL0HkmW8c+A3doGk5Og/YW4="
    },
    "to-object-path": {
      "version": "0.3.0",
      "resolved": "https://registry.npmjs.org/to-object-path/-/to-object-path-0.3.0.tgz",
      "integrity": "sha1-KXWIt7Dn4KwI4E5nL4XB9JmeF68=",
      "requires": {
        "kind-of": "^3.0.2"
      },
      "dependencies": {
        "kind-of": {
          "version": "3.2.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
          "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
          "requires": {
            "is-buffer": "^1.1.5"
          }
        }
      }
    },
    "to-regex": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/to-regex/-/to-regex-3.0.2.tgz",
      "integrity": "sha512-FWtleNAtZ/Ki2qtqej2CXTOayOH9bHDQF+Q48VpWyDXjbYxA4Yz8iDB31zXOBUlOHHKidDbqGVrTUvQMPmBGBw==",
      "requires": {
        "define-property": "^2.0.2",
        "extend-shallow": "^3.0.2",
        "regex-not": "^1.0.2",
        "safe-regex": "^1.1.0"
      },
      "dependencies": {
        "extend-shallow": {
          "version": "3.0.2",
          "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-3.0.2.tgz",
          "integrity": "sha1-Jqcarwc7OfshJxcnRhMcJwQCjbg=",
          "requires": {
            "assign-symbols": "^1.0.0",
            "is-extendable": "^1.0.1"
          }
        },
        "is-extendable": {
          "version": "1.0.1",
          "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-1.0.1.tgz",
          "integrity": "sha512-arnXMxT1hhoKo9k1LZdmlNyJdDDfy2v0fXjFlmok4+i8ul/6WlbVge9bhM74OpNPQPMGUToDtz+KXa1PneJxOA==",
          "requires": {
            "is-plain-object": "^2.0.4"
          }
        }
      }
    },
    "to-regex-range": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/to-regex-range/-/to-regex-range-2.1.1.tgz",
      "integrity": "sha1-fIDBe53+vlmeJzZ+DU3VWQFB2zg=",
      "requires": {
        "is-number": "^3.0.0",
        "repeat-string": "^1.6.1"
      },
      "dependencies": {
        "is-number": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/is-number/-/is-number-3.0.0.tgz",
          "integrity": "sha1-JP1iAaR4LPUFYcgQJ2r8fRLXEZU=",
          "requires": {
            "kind-of": "^3.0.2"
          }
        },
        "kind-of": {
          "version": "3.2.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
          "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
          "requires": {
            "is-buffer": "^1.1.5"
          }
        }
      }
    },
    "toposort": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/toposort/-/toposort-2.0.2.tgz",
      "integrity": "sha1-riF2gXXRVZ1IvvNUILL0li8JwzA="
    },
    "trim-right": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/trim-right/-/trim-right-1.0.1.tgz",
      "integrity": "sha1-yy4SAwZ+DI3h9hQJS5/kVwTqYAM="
    },
    "ts-invariant": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/ts-invariant/-/ts-invariant-0.2.1.tgz",
      "integrity": "sha512-Z/JSxzVmhTo50I+LKagEISFJW3pvPCqsMWLamCTX8Kr3N5aMrnGOqcflbe5hLUzwjvgPfnLzQtHZv0yWQ+FIHg==",
      "requires": {
        "tslib": "^1.9.3"
      }
    },
    "tslib": {
      "version": "1.9.3",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-1.9.3.tgz",
      "integrity": "sha512-4krF8scpejhaOgqzBEcGM7yDIEfi0/8+8zDRZhNZZ2kjmHJ4hv3zCbQWxoJGz1iw5U0Jl0nma13xzHXcncMavQ=="
    },
    "tween-functions": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/tween-functions/-/tween-functions-1.2.0.tgz",
      "integrity": "sha1-GuOlDnxguz3vd06scHrLynO7w/8="
    },
    "typedarray": {
      "version": "0.0.6",
      "resolved": "https://registry.npmjs.org/typedarray/-/typedarray-0.0.6.tgz",
      "integrity": "sha1-hnrHTjhkGHsdPUfZlqeOxciDB3c="
    },
    "ua-parser-js": {
      "version": "0.7.19",
      "resolved": "https://registry.npmjs.org/ua-parser-js/-/ua-parser-js-0.7.19.tgz",
      "integrity": "sha512-T3PVJ6uz8i0HzPxOF9SWzWAlfN/DavlpQqepn22xgve/5QecC+XMCAtmUNnY7C9StehaV6exjUCI801lOI7QlQ=="
    },
    "uglify-es": {
      "version": "3.3.9",
      "resolved": "https://registry.npmjs.org/uglify-es/-/uglify-es-3.3.9.tgz",
      "integrity": "sha512-r+MU0rfv4L/0eeW3xZrd16t4NZfK8Ld4SWVglYBb7ez5uXFWHuVRs6xCTrf1yirs9a4j4Y27nn7SRfO6v67XsQ==",
      "requires": {
        "commander": "~2.13.0",
        "source-map": "~0.6.1"
      },
      "dependencies": {
        "commander": {
          "version": "2.13.0",
          "resolved": "https://registry.npmjs.org/commander/-/commander-2.13.0.tgz",
          "integrity": "sha512-MVuS359B+YzaWqjCL/c+22gfryv+mCBPHAv3zyVI2GN8EY6IRP8VwtasXn8jyyhvvq84R4ImN1OKRtcbIasjYA=="
        },
        "source-map": {
          "version": "0.6.1",
          "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.6.1.tgz",
          "integrity": "sha512-UjgapumWlbMhkBgzT7Ykc5YXUT46F0iKu8SGXq0bcwP5dz/h0Plj6enJqjz1Zbq2l5WaqYnrVbwWOWMyF3F47g=="
        }
      }
    },
    "ultron": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/ultron/-/ultron-1.0.2.tgz",
      "integrity": "sha1-rOEWq1V80Zc4ak6I9GhTeMiy5Po="
    },
    "unicode-canonical-property-names-ecmascript": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/unicode-canonical-property-names-ecmascript/-/unicode-canonical-property-names-ecmascript-1.0.4.tgz",
      "integrity": "sha512-jDrNnXWHd4oHiTZnx/ZG7gtUTVp+gCcTTKr8L0HjlwphROEW3+Him+IpvC+xcJEFegapiMZyZe02CyuOnRmbnQ=="
    },
    "unicode-match-property-ecmascript": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/unicode-match-property-ecmascript/-/unicode-match-property-ecmascript-1.0.4.tgz",
      "integrity": "sha512-L4Qoh15vTfntsn4P1zqnHulG0LdXgjSO035fEpdtp6YxXhMT51Q6vgM5lYdG/5X3MjS+k/Y9Xw4SFCY9IkR0rg==",
      "requires": {
        "unicode-canonical-property-names-ecmascript": "^1.0.4",
        "unicode-property-aliases-ecmascript": "^1.0.4"
      }
    },
    "unicode-match-property-value-ecmascript": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/unicode-match-property-value-ecmascript/-/unicode-match-property-value-ecmascript-1.0.2.tgz",
      "integrity": "sha512-Rx7yODZC1L/T8XKo/2kNzVAQaRE88AaMvI1EF/Xnj3GW2wzN6fop9DDWuFAKUVFH7vozkz26DzP0qyWLKLIVPQ=="
    },
    "unicode-property-aliases-ecmascript": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/unicode-property-aliases-ecmascript/-/unicode-property-aliases-ecmascript-1.0.4.tgz",
      "integrity": "sha512-2WSLa6OdYd2ng8oqiGIWnJqyFArvhn+5vgx5GTxMbUYjCYKUcuKS62YLFF0R/BDGlB1yzXjQOLtPAfHsgirEpg=="
    },
    "union-value": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/union-value/-/union-value-1.0.0.tgz",
      "integrity": "sha1-XHHDTLW61dzr4+oM0IIHulqhrqQ=",
      "requires": {
        "arr-union": "^3.1.0",
        "get-value": "^2.0.6",
        "is-extendable": "^0.1.1",
        "set-value": "^0.4.3"
      },
      "dependencies": {
        "arr-union": {
          "version": "3.1.0",
          "resolved": "https://registry.npmjs.org/arr-union/-/arr-union-3.1.0.tgz",
          "integrity": "sha1-45sJrqne+Gao8gbiiK9jkZuuOcQ="
        },
        "extend-shallow": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
          "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
          "requires": {
            "is-extendable": "^0.1.0"
          }
        },
        "set-value": {
          "version": "0.4.3",
          "resolved": "https://registry.npmjs.org/set-value/-/set-value-0.4.3.tgz",
          "integrity": "sha1-fbCPnT0i3H945Trzw79GZuzfzPE=",
          "requires": {
            "extend-shallow": "^2.0.1",
            "is-extendable": "^0.1.1",
            "is-plain-object": "^2.0.1",
            "to-object-path": "^0.3.0"
          }
        }
      }
    },
    "unpipe": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz",
      "integrity": "sha1-sr9O6FFKrmFltIF4KdIbLvSZBOw="
    },
    "unset-value": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/unset-value/-/unset-value-1.0.0.tgz",
      "integrity": "sha1-g3aHP30jNRef+x5vw6jtDfyKtVk=",
      "requires": {
        "has-value": "^0.3.1",
        "isobject": "^3.0.0"
      },
      "dependencies": {
        "has-value": {
          "version": "0.3.1",
          "resolved": "https://registry.npmjs.org/has-value/-/has-value-0.3.1.tgz",
          "integrity": "sha1-ex9YutpiyoJ+wKIHgCVlSEWZXh8=",
          "requires": {
            "get-value": "^2.0.3",
            "has-values": "^0.1.4",
            "isobject": "^2.0.0"
          },
          "dependencies": {
            "isobject": {
              "version": "2.1.0",
              "resolved": "https://registry.npmjs.org/isobject/-/isobject-2.1.0.tgz",
              "integrity": "sha1-8GVWEJaj8dou9GJy+BXIQNh+DIk=",
              "requires": {
                "isarray": "1.0.0"
              }
            }
          }
        },
        "has-values": {
          "version": "0.1.4",
          "resolved": "https://registry.npmjs.org/has-values/-/has-values-0.1.4.tgz",
          "integrity": "sha1-bWHeldkd/Km5oCCJrThL/49it3E="
        },
        "isobject": {
          "version": "3.0.1",
          "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
          "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8="
        }
      }
    },
    "uri-js": {
      "version": "4.2.2",
      "resolved": "https://registry.npmjs.org/uri-js/-/uri-js-4.2.2.tgz",
      "integrity": "sha512-KY9Frmirql91X2Qgjry0Wd4Y+YTdrdZheS8TFwvkbLWf/G5KNJDCh6pKL5OZctEW4+0Baa5idK2ZQuELRwPznQ==",
      "requires": {
        "punycode": "^2.1.0"
      }
    },
    "uri-parser": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/uri-parser/-/uri-parser-1.0.1.tgz",
      "integrity": "sha512-TRjjM2M83RD9jIIYttNj7ghUQTKSov+WXZbQIMM8DxY1R1QdJEGWNKKMYCxyeOw1p9re2nQ85usM6dPTVtox1g=="
    },
    "urix": {
      "version": "0.1.0",
      "resolved": "https://registry.npmjs.org/urix/-/urix-0.1.0.tgz",
      "integrity": "sha1-2pN/emLiH+wf0Y1Js1wpNQZ6bHI="
    },
    "url-join": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/url-join/-/url-join-4.0.0.tgz",
      "integrity": "sha1-TTNA6AfTdzvamZH4MFrNzCpmXSo="
    },
    "url-loader": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/url-loader/-/url-loader-1.1.2.tgz",
      "integrity": "sha512-dXHkKmw8FhPqu8asTc1puBfe3TehOCo2+RmOOev5suNCIYBcT626kxiWg1NBVkwc4rO8BGa7gP70W7VXuqHrjg==",
      "requires": {
        "loader-utils": "^1.1.0",
        "mime": "^2.0.3",
        "schema-utils": "^1.0.0"
      },
      "dependencies": {
        "mime": {
          "version": "2.4.0",
          "resolved": "https://registry.npmjs.org/mime/-/mime-2.4.0.tgz",
          "integrity": "sha512-ikBcWwyqXQSHKtciCcctu9YfPbFYZ4+gbHEmE0Q8jzcTYQg5dHCr3g2wwAZjPoJfQVXZq6KXAjpXOTf5/cjT7w=="
        }
      }
    },
    "use": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/use/-/use-3.1.1.tgz",
      "integrity": "sha512-cwESVXlO3url9YWlFW/TA9cshCEhtu7IKJ/p5soJ/gGpj7vbvFrAY/eIioQ6Dw23KjZhYgiIo8HOs1nQ2vr/oQ=="
    },
    "util-deprecate": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz",
      "integrity": "sha1-RQ1Nyfpw3nMnYvvS1KKJgUGaDM8="
    },
    "utils-merge": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/utils-merge/-/utils-merge-1.0.1.tgz",
      "integrity": "sha1-n5VxD1CiZ5R7LMwSR0HBAoQn5xM="
    },
    "uuid": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/uuid/-/uuid-3.0.1.tgz",
      "integrity": "sha1-ZUS7ot/ajBzxfmKaOjBeK7H+5sE="
    },
    "uuid-js": {
      "version": "0.7.5",
      "resolved": "https://registry.npmjs.org/uuid-js/-/uuid-js-0.7.5.tgz",
      "integrity": "sha1-bIhtAqU9LUDc8l2RoXC0p7JblNA="
    },
    "validate-npm-package-license": {
      "version": "3.0.4",
      "resolved": "https://registry.npmjs.org/validate-npm-package-license/-/validate-npm-package-license-3.0.4.tgz",
      "integrity": "sha512-DpKm2Ui/xN7/HQKCtpZxoRWBhZ9Z0kqtygG8XCgNQ8ZlDnxuQmWhj566j8fN4Cu3/JmbhsDo7fcAJq4s9h27Ew==",
      "requires": {
        "spdx-correct": "^3.0.0",
        "spdx-expression-parse": "^3.0.0"
      }
    },
    "vary": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/vary/-/vary-1.1.2.tgz",
      "integrity": "sha1-IpnwLG3tMNSllhsLn3RSShj2NPw="
    },
    "walker": {
      "version": "1.0.7",
      "resolved": "https://registry.npmjs.org/walker/-/walker-1.0.7.tgz",
      "integrity": "sha1-L3+bj9ENZ3JisYqITijRlhjgKPs=",
      "requires": {
        "makeerror": "1.0.x"
      }
    },
    "watch": {
      "version": "0.18.0",
      "resolved": "https://registry.npmjs.org/watch/-/watch-0.18.0.tgz",
      "integrity": "sha1-KAlUdsbffJDJYxOJkMClQj60uYY=",
      "requires": {
        "exec-sh": "^0.2.0",
        "minimist": "^1.2.0"
      }
    },
    "whatwg-fetch": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/whatwg-fetch/-/whatwg-fetch-2.0.4.tgz",
      "integrity": "sha512-dcQ1GWpOD/eEQ97k66aiEVpNnapVj90/+R+SXTPYGHpYBBypfKJEQjLrvMZ7YXbKm21gXd4NcuxUTjiv1YtLng=="
    },
    "which": {
      "version": "1.3.1",
      "resolved": "https://registry.npmjs.org/which/-/which-1.3.1.tgz",
      "integrity": "sha512-HxJdYWq1MTIQbJ3nw0cqssHoTNU267KlrDuGZ1WYlxDStUtKUhOaJmh112/TZmHxxUfuJqPXSOm7tDyas0OSIQ==",
      "requires": {
        "isexe": "^2.0.0"
      }
    },
    "which-module": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/which-module/-/which-module-2.0.0.tgz",
      "integrity": "sha1-2e8H3Od7mQK4o6j6SzHD4/fm6Ho="
    },
    "wordwrap": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/wordwrap/-/wordwrap-1.0.0.tgz",
      "integrity": "sha1-J1hIEIkUVqQXHI0CJkQa3pDLyus="
    },
    "wrap-ansi": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/wrap-ansi/-/wrap-ansi-2.1.0.tgz",
      "integrity": "sha1-2Pw9KE3QV5T+hJc8rs3Rz4JP3YU=",
      "requires": {
        "string-width": "^1.0.1",
        "strip-ansi": "^3.0.1"
      },
      "dependencies": {
        "string-width": {
          "version": "1.0.2",
          "resolved": "https://registry.npmjs.org/string-width/-/string-width-1.0.2.tgz",
          "integrity": "sha1-EYvfW4zcUaKn5w0hHgfisLmxB9M=",
          "requires": {
            "code-point-at": "^1.0.0",
            "is-fullwidth-code-point": "^1.0.0",
            "strip-ansi": "^3.0.0"
          }
        }
      }
    },
    "wrappy": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz",
      "integrity": "sha1-tSQ9jz7BqjXxNkYFvA0QNuMKtp8="
    },
    "write-file-atomic": {
      "version": "1.3.4",
      "resolved": "https://registry.npmjs.org/write-file-atomic/-/write-file-atomic-1.3.4.tgz",
      "integrity": "sha1-+Aek8LHZ6ROuekgRLmzDrxmRtF8=",
      "requires": {
        "graceful-fs": "^4.1.11",
        "imurmurhash": "^0.1.4",
        "slide": "^1.1.5"
      }
    },
    "ws": {
      "version": "1.1.5",
      "resolved": "https://registry.npmjs.org/ws/-/ws-1.1.5.tgz",
      "integrity": "sha512-o3KqipXNUdS7wpQzBHSe180lBGO60SoK0yVo3CYJgb2MkobuWuBX6dhkYP5ORCLd55y+SaflMOV5fqAB53ux4w==",
      "requires": {
        "options": ">=0.0.5",
        "ultron": "1.0.x"
      }
    },
    "xcode": {
      "version": "0.9.3",
      "resolved": "https://registry.npmjs.org/xcode/-/xcode-0.9.3.tgz",
      "integrity": "sha1-kQqJwWrubMC0LKgFptC0z4chHPM=",
      "requires": {
        "pegjs": "^0.10.0",
        "simple-plist": "^0.2.1",
        "uuid": "3.0.1"
      }
    },
    "xmlbuilder": {
      "version": "9.0.7",
      "resolved": "https://registry.npmjs.org/xmlbuilder/-/xmlbuilder-9.0.7.tgz",
      "integrity": "sha1-Ey7mPS7FVlxVfiD0wi35rKaGsQ0="
    },
    "xmldoc": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/xmldoc/-/xmldoc-0.4.0.tgz",
      "integrity": "sha1-0lciS+g5PqrL+DfvIn/Y7CWzaIg=",
      "requires": {
        "sax": "~1.1.1"
      }
    },
    "xmldom": {
      "version": "0.1.27",
      "resolved": "https://registry.npmjs.org/xmldom/-/xmldom-0.1.27.tgz",
      "integrity": "sha1-1QH5ezvbQDr4757MIFcxh6rawOk="
    },
    "xpipe": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/xpipe/-/xpipe-1.0.5.tgz",
      "integrity": "sha1-jdi/Rfw/f1Xw4FS4ePQ6YmFNr98="
    },
    "xtend": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/xtend/-/xtend-4.0.1.tgz",
      "integrity": "sha1-pcbVMr5lbiPbgg77lDofBJmNY68="
    },
    "y18n": {
      "version": "3.2.1",
      "resolved": "https://registry.npmjs.org/y18n/-/y18n-3.2.1.tgz",
      "integrity": "sha1-bRX7qITAhnnA136I53WegR4H+kE="
    },
    "yallist": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/yallist/-/yallist-2.1.2.tgz",
      "integrity": "sha1-HBH5IY8HYImkfdUS+TxmmaaoHVI="
    },
    "yargs": {
      "version": "9.0.1",
      "resolved": "https://registry.npmjs.org/yargs/-/yargs-9.0.1.tgz",
      "integrity": "sha1-UqzCP+7Kw0BCB47njAwAf1CF20w=",
      "requires": {
        "camelcase": "^4.1.0",
        "cliui": "^3.2.0",
        "decamelize": "^1.1.1",
        "get-caller-file": "^1.0.1",
        "os-locale": "^2.0.0",
        "read-pkg-up": "^2.0.0",
        "require-directory": "^2.1.1",
        "require-main-filename": "^1.0.1",
        "set-blocking": "^2.0.0",
        "string-width": "^2.0.0",
        "which-module": "^2.0.0",
        "y18n": "^3.2.1",
        "yargs-parser": "^7.0.0"
      }
    },
    "yargs-parser": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/yargs-parser/-/yargs-parser-7.0.0.tgz",
      "integrity": "sha1-jQrELxbqVd69MyyvTEA4s+P139k=",
      "requires": {
        "camelcase": "^4.1.0"
      }
    },
    "yup": {
      "version": "0.26.10",
      "resolved": "https://registry.npmjs.org/yup/-/yup-0.26.10.tgz",
      "integrity": "sha512-keuNEbNSnsOTOuGCt3UJW69jDE3O4P+UHAakO7vSeFMnjaitcmlbij/a3oNb9g1Y1KvSKH/7O1R2PQ4m4TRylw==",
      "requires": {
        "@babel/runtime": "7.0.0",
        "fn-name": "~2.0.1",
        "lodash": "^4.17.10",
        "property-expr": "^1.5.0",
        "synchronous-promise": "^2.0.5",
        "toposort": "^2.0.2"
      },
      "dependencies": {
        "@babel/runtime": {
          "version": "7.0.0",
          "resolved": "https://registry.npmjs.org/@babel/runtime/-/runtime-7.0.0.tgz",
          "integrity": "sha512-7hGhzlcmg01CvH1EHdSPVXYX1aJ8KCEyz6I9xYIi/asDtzBPMyMhVibhM/K6g/5qnKBwjZtp10bNZIEFTRW1MA==",
          "requires": {
            "regenerator-runtime": "^0.12.0"
          }
        },
        "regenerator-runtime": {
          "version": "0.12.1",
          "resolved": "https://registry.npmjs.org/regenerator-runtime/-/regenerator-runtime-0.12.1.tgz",
          "integrity": "sha512-odxIc1/vDlo4iZcfXqRYFj0vpXFNoGdKMAUieAlFYO6m/nl5e9KR/beGf41z4a1FI+aQgtjhuaSlDxQ0hmkrHg=="
        }
      }
    },
    "zen-observable": {
      "version": "0.8.13",
      "resolved": "https://registry.npmjs.org/zen-observable/-/zen-observable-0.8.13.tgz",
      "integrity": "sha512-fa+6aDUVvavYsefZw0zaZ/v3ckEtMgCFi30sn91SEZea4y/6jQp05E3omjkX91zV6RVdn15fqnFZ6RKjRGbp2g=="
    },
    "zen-observable-ts": {
      "version": "0.8.15",
      "resolved": "https://registry.npmjs.org/zen-observable-ts/-/zen-observable-ts-0.8.15.tgz",
      "integrity": "sha512-sXKPWiw6JszNEkRv5dQ+lQCttyjHM2Iks74QU5NP8mMPS/NrzTlHDr780gf/wOBqmHkPO6NCLMlsa+fAQ8VE8w==",
      "requires": {
        "zen-observable": "^0.8.0"
      }
    }
  }
}
© 2020 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
