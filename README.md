# Sub Zero (Contracts)

> An efficient way to mine and transact vanity addresses, tokenized as
> [ERC-721](https://eips.ethereum.org/EIPS/eip-721) tokens.


## Deployments

**Micro Create2 Factory**

Deployed across chains at: `0x6D9FB3C412a269Df566a5c92b85a8dc334F0A797`

Deployed from [`CreateX Factory`](https://blockscan.com/address/0xba5Ed099633D3B313e4D5F7bdc1305d3c28ba5Ed) with calldata:

```
deployCreate2(bytes32 salt,bytes initCode)
    salt: 0x0000000000000000000000000000000000000000000000000000000000000000
    initCode: 0x7160203d3581360380833d373d34f53d523df33d526012600ef3
```

**Nonce Increaser**

Deployed across chains at: `0x00000000000001e4a82b33373de1334e7d8f4879`

Deployed from [`Micro Create2`](https://blockscan.com/address/0x6D9FB3C412a269Df566a5c92b85a8dc334F0A797) with calldata:

```
0x0000000000000000000000000000000000000000b07f6240b4f3c700ed9c26556104d980600a3d393df33d353d1a8060101161031357806080161561019f578060801161019f573d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df0505b806040161561026b573d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df0505b80602016156102d7573d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df0505b8060101615610313573d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3df03df03df03df03df03df03df03df03df03df03df03df03df03df03df03df0505b7f03420372039f03c903f0041404350453046e0486049b04ad04bc04c804d104d790600f1660041b1c61ffff16565b3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3df03df03df03df03df03df03df03df03df03df03df03df03df03df03df0005b3d3d3d3d3d3d3d3d3d3d3d3d3d3d3d3df03df03df03df03df03df03df03df03df03df03df03df03df03df0005b3d3d3d3d3d3d3d3d3d3d3d3d3d3d3df03df03df03df03df03df03df03df03df03df03df03df03df0005b3d3d3d3d3d3d3d3d3d3d3d3d3d3df03df03df03df03df03df03df03df03df03df03df03df0005b3d3d3d3d3d3d3d3d3d3d3d3d3df03df03df03df03df03df03df03df03df03df03df0005b3d3d3d3d3d3d3d3d3d3d3d3df03df03df03df03df03df03df03df03df03df0005b3d3d3d3d3d3d3d3d3d3d3df03df03df03df03df03df03df03df03df0005b3d3d3d3d3d3d3d3d3d3df03df03df03df03df03df03df03df0005b3d3d3d3d3d3d3d3d3df03df03df03df03df03df03df0005b3d3d3d3d3d3d3d3df03df03df03df03df03df0005b3d3d3d3d3d3d3df03df03df03df03df0005b3d3d3d3d3d3df03df03df03df0005b3d3d3d3d3df03df03df0005b3d3d3d3df03df0005b3d3d3df0005b00
```

**Tradable Addresses**

Deployed across chains at: `0x000000000000b361194cfe6312ee3210d53c15aa`

Deployed from [`Micro Create2`](https://blockscan.com/address/0x6D9FB3C412a269Df566a5c92b85a8dc334F0A797) with calldata:

```
0x000000000000000000000000000000000000000094038e9be572f900652a472c6101c06040527fa428e38531249fcbdc58d8acd828f93f88dc927ed06686d4966329a00d0e402c610140527f1decbcf04b355d500cbc3bd83c892545b4df34bd5b2c9d91b9f7f8165e2095c3610160527fd7297ff8cc8b0abf17e5590f0b14e1c876bb758ce21d250e9d39e37f61d77f5e610180527f3d27e7c5806b97e91e45fdf6c7d4b7e7b8aa85f091a2fa2999a87ea3bafc7ca66101a0523480156100a557600080fd5b50604051612d89380380612d898339810160408190526100c491610263565b306080524660a0526000806100d761018d565b815160209283012081519183019190912060c082905260e0819052604080517f91ab3d17e3a50a9d89e63fd30b92be7f5336b03b287bb946787a83a9d62a276681529384019290925290820152306060820181815260808084207f8b73c3c69bb8fe3d512ecc4cf759cc79239f7b179b0ffacaa9a75d522b39400f85524690925283019190915260a09091206101005261012052506101739050565b61017c816101bc565b6101878160006101f8565b50610293565b606080610198610243565b604051806040016040528060038152602001620312e360ec1b815250915091509091565b6001600160a01b0316638b78c6d8198190558060007f8be0079c531659141344cd1fd0a4f28419497f9722a3daafe3b4186f6b6457e08180a350565b6001600160601b03166127108082111561021a5763350a88b36000526004601cfd5b8260601b806102315763b4457eaa6000526004601cfd5b90911768aa4ec00224afccfdb7555050565b6060604051806060016040528060228152602001612d6760229139905090565b60006020828403121561027557600080fd5b81516001600160a01b038116811461028c57600080fd5b9392505050565b60805160a05160c05160e05161010051610120516101405161016051610180516101a051612a3c61032b600039600061185e01526000610e5e0152600081816107ac01526116ac0152600061144e0152600081816105bf01526120940152600081816105100152611b730152600050506000505060008181611b0b015261202c015260008181611ae801526120090152612a3c6000f3fe6080604052600436106102d55760003560e01c80638900400311610179578063c87b56dd116100d6578063e985e9c51161008a578063f2fde38b11610064578063f2fde38b1461088c578063f3fef3a31461089f578063fee81cf4146108bf576102dc565b8063e985e9c514610823578063f04e283e14610859578063f13695681461086c576102dc565b8063e17120c7116100bb578063e17120c7146107ce578063e7139a09146107ee578063e8a3d4851461080e576102dc565b8063c87b56dd1461077a578063d2744d791461079a576102dc565b8063a22cb4651161012d578063b70e36f011610112578063b70e36f014610701578063b79269ee14610747578063b88d4fde14610767576102dc565b8063a22cb465146106a8578063b09afec1146106c8576102dc565b80638da5cb5b1161015e5780638da5cb5b1461060e5780638e0055531461064257806395d89b4114610662576102dc565b806389004003146105ad5780638ada6b0f146105e1576102dc565b806331c7774411610232578063598e6ca9116101e65780636352211e116101c05780636352211e1461056557806370a0823114610585578063715018a6146105a5576102dc565b8063598e6ca9146104fe5780636112e8ac1461053257806361ff715f14610552576102dc565b806342842e0e1161021757806342842e0e146104c357806354d1f13d146104d657806356d3163d146104de576102dc565b806331c777441461049057806336e79a5a146104a3576102dc565b8063135a9c811161028957806324a9d8531161026e57806324a9d853146103f6578063256929621461043c5780632a55205a14610444576102dc565b8063135a9c81146103b557806323b872dd146103e3576102dc565b8063081812fc116102ba578063081812fc1461033d578063095ea7b31461038257806311a800bc14610395576102dc565b806301ffc9a7146102e657806306fdde031461031b576102dc565b366102dc57005b6102e46108f2565b005b3480156102f257600080fd5b506103066103013660046122ed565b6109e4565b60405190151581526020015b60405180910390f35b34801561032757600080fd5b50610330610a2f565b6040516103129190612353565b34801561034957600080fd5b5061035d6103583660046123a4565b610a4f565b60405173ffffffffffffffffffffffffffffffffffffffff9091168152602001610312565b6102e46103903660046123e1565b610aa3565b3480156103a157600080fd5b5061035d6103b03660046123a4565b610ab2565b3480156103c157600080fd5b506103d56103d03660046123a4565b610b0d565b604051908152602001610312565b6102e46103f136600461240b565b610b51565b34801561040257600080fd5b506001546104299074010000000000000000000000000000000000000000900461ffff1681565b60405161ffff9091168152602001610312565b6102e4610c92565b34801561045057600080fd5b5061046461045f366004612447565b610ce2565b6040805173ffffffffffffffffffffffffffffffffffffffff9093168352602083019190915201610312565b6102e461049e3660046124c3565b610d55565b3480156104af57600080fd5b506102e46104be366004612574565b610f55565b6102e46104d136600461240b565b610f6e565b6102e4610f9b565b3480156104ea57600080fd5b506102e46104f9366004612598565b610fd7565b34801561050a57600080fd5b506103d57f000000000000000000000000000000000000000000000000000000000000000081565b34801561053e57600080fd5b506102e461054d3660046125b3565b6110d2565b61035d6105603660046125ef565b61116b565b34801561057157600080fd5b5061035d6105803660046123a4565b61120c565b34801561059157600080fd5b506103d56105a0366004612598565b61126c565b6102e46112bc565b3480156105b957600080fd5b506103d57f000000000000000000000000000000000000000000000000000000000000000081565b3480156105ed57600080fd5b5060015461035d9073ffffffffffffffffffffffffffffffffffffffff1681565b34801561061a57600080fd5b507fffffffffffffffffffffffffffffffffffffffffffffffffffffffff748739275461035d565b34801561064e57600080fd5b506102e461065d366004612574565b6112d0565b34801561066e57600080fd5b5060408051808201909152600481527f41444452000000000000000000000000000000000000000000000000000000006020820152610330565b3480156106b457600080fd5b506102e46106c336600461263b565b611398565b3480156106d457600080fd5b506106e86106e33660046123a4565b6113ee565b60408051921515835260ff909116602083015201610312565b34801561070d57600080fd5b506102e461071c3660046123a4565b33600090815260208181526040808320600885901c845290915290208054600160ff84161b17905550565b34801561075357600080fd5b506102e4610762366004612677565b61143f565b6102e46107753660046126ef565b6114da565b34801561078657600080fd5b506103306107953660046123a4565b611535565b3480156107a657600080fd5b506103d57f000000000000000000000000000000000000000000000000000000000000000081565b3480156107da57600080fd5b506103066107e93660046123e1565b611661565b3480156107fa57600080fd5b5061035d61080936600461275e565b6116a4565b34801561081a57600080fd5b506103306116eb565b34801561082f57600080fd5b5061030661083e36600461278a565b601c52670a5a2e7a000000006008526000526030600c205490565b6102e4610867366004612598565b61178a565b34801561087857600080fd5b506102e46108873660046127b4565b6117c7565b6102e461089a366004612598565b6118fd565b3480156108ab57600080fd5b506102e46108ba3660046123e1565b611924565b3480156108cb57600080fd5b506103d56108da366004612598565b63389a75e1600c908152600091909152602090205490565b366108fb573636f35b6000805b8036821061090d57506109c3565b81357ffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffc83011860001a60018084019350816109b3577fffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff85526002830193357ffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffd84011860001a607f8082116109a2578282013888395b169490940190930192506108ff9050565b81855380850194505050506108ff565b50600038826000305af490503d6000803e806109de573d6000fd5b503d6000f35b6000632a55205a60e083901c9081146301ffc9a7919091141780610a295750610a29826301ffc9a760e09190911c9081146380ac58cd821417635b5e139f9091141790565b92915050565b60606040518060600160405280602281526020016129e560229139905090565b6000816000527f7d8825530a5a2e7a000000000000000000000000000000000000000000000000601c52602060002082018201805460601b610a995763ceea21b66000526004601cfd5b6001015492915050565b610aae338383611976565b5050565b6000806000610ac0846113ee565b9150915081610afb576040517fceea21b600000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b610b0584826116a4565b949350505050565b600154600090610b3b9074010000000000000000000000000000000000000000900461ffff1661271061286c565b610b476127108461287f565b610a299190612896565b60008181527f7d8825530a5a2e7a0000000000000000000000000000000000000000000000003317601c526020902081018101805473ffffffffffffffffffffffffffffffffffffffff9485169493841693811691908286148302610bc55767ceea21b6a1148100831560021b526004601cfd5b856000528160010154925082331486331417610bf3576030600c2054610bf357634b6e7f186000526004601cfd5b8215610c0157600082600101555b85851818905550601c600c81812080547fffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff019055600084905220805460010163ffffffff81168402610c625767ea553b3401336cea841560021b526004601cfd5b90558082847fddf252ad1be2c89b69c2b068fc378daa952ba7f163c4a11628f55a4df523b3ef600038a45b505050565b60006202a30067ffffffffffffffff164201905063389a75e1600c5233600052806020600c2055337fdbf36a107da19e49527a7176a1babf963b4b0ff8cde35ee35d6cd8f1f9ac7e1d600080a250565b600082815268aa4ec00224afccfdb76020526040812054606081901c91906127109083610d16576020515490508060601c93505b606084901b18847fffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff829004811182023d3d3e9396930204935090915050565b610d5e83611a2c565b6000610d6a8a60601c90565b9050610d768186611a66565b6000610d8188610b0d565b905034811115610dbd576040517f1101129400000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b73ffffffffffffffffffffffffffffffffffffffff871615801590610df8575073ffffffffffffffffffffffffffffffffffffffff87163314155b8015610e215750610e1f8733601c52670a5a2e7a000000006008526000526030600c205490565b155b15610e58576040517fd7fce0a800000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b604080517f000000000000000000000000000000000000000000000000000000000000000060208201529081018c905260ff8b1660608201526080810189905273ffffffffffffffffffffffffffffffffffffffff808b1660a0830152881660c082015260e081018790526101008101869052600090610ef290610120015b60405160208183030381529060405280519060200120611ae4565b9050610f0083828787611ba7565b610f0b8d8d8d611be9565b348290038915610f3557610f3573ffffffffffffffffffffffffffffffffffffffff8c168b611c41565b8015610f4557610f453382611c41565b5050505050505050505050505050565b610f5d611c5d565b610f6b338261ffff16611c93565b50565b610f79838383610b51565b813b15610c8d57610c8d83838360405180602001604052806000815250611ce3565b63389a75e1600c523360005260006020600c2055337ffa7b8eab7da67f412cc9575ed43464468f9bfbae89d1675917346ca6d8fe3c92600080a2565b610fdf611c5d565b60015473ffffffffffffffffffffffffffffffffffffffff16801580159061102b57506e0100000000000000000000000000008173ffffffffffffffffffffffffffffffffffffffff16105b15611062576040517f63e35e6700000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b600180547fffffffffffffffffffffffff00000000000000000000000000000000000000001673ffffffffffffffffffffffffffffffffffffffff84169081179091556040517f869c6ebc45b752b03abf2550b2114eed8d11ba3a40ea9da00d3ef99fd004af7290600090a25050565b60006110de8360601c90565b90503373ffffffffffffffffffffffffffffffffffffffff82161480159061112357506111218133601c52670a5a2e7a000000006008526000526030600c205490565b155b1561115a576040517f4b6e7f1800000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b611165848484611be9565b50505050565b60006111773385611d6f565b6000611182856113ee565b91505070e1334e7d8f48795af49247f034521b34f36011527f60288060093d393df36001600581360334348434363434376d01e4a82b33373d600052846031600034f5604051828153848660018301376020600060018701836000865af1915050600051925060203d1483151081166112035763301164256000526004601cfd5b50509392505050565b60008181527f7d8825530a5a2e7a000000000000000000000000000000000000000000000000601c5260209020810181015473ffffffffffffffffffffffffffffffffffffffff16806112675763ceea21b66000526004601cfd5b919050565b60008161128157638f4eb6046000526004601cfd5b7f7d8825530a5a2e7a000000000000000000000000000000000000000000000000601c528160005263ffffffff601c600c2054169050919050565b6112c4611c5d565b6112ce6000611e7d565b565b6112d8611c5d565b6127108161ffff1610611317576040517f58d620b300000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b600180547fffffffffffffffffffff0000ffffffffffffffffffffffffffffffffffffffff167401000000000000000000000000000000000000000061ffff8416908102919091179091556040519081527faab062e3faf62b6c9a0f8e62af66e0310e27127a8c871a67be7dd4d93de6da539060200160405180910390a150565b801515905081601c52670a5a2e7a0000000060085233600052806030600c2055806000528160601b60601c337f17307eab39ab6107e8899845ad3d59bd9653f200f220920489ca2b5937696c3160206000a35050565b600080600061142e8460008181527f7d8825530a5a2e7a000000000000000000000000000000000000000000000000601c52602090208101015460a01c90565b610100811615159590945092505050565b61144883611a2c565b604080517f0000000000000000000000000000000000000000000000000000000000000000602082015273ffffffffffffffffffffffffffffffffffffffff87169181019190915260608101859052608081018490526000906114ad9060a001610ed7565b90506114bb87828585611ba7565b6114c58786611a66565b6114d187876001611ea2565b50505050505050565b6114e5858585610b51565b833b1561152e5761152e85858585858080601f016020809104026020016040519081016040528093929190818152602001838380828437600092019190915250611ce392505050565b5050505050565b6060600080611543846113ee565b915091508161157e576040517fceea21b600000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b600061158a85836116a4565b9050611594611f1b565b6040517f3fec213e0000000000000000000000000000000000000000000000000000000081526004810187905273ffffffffffffffffffffffffffffffffffffffff838116602483015260ff851660448301529190911690633fec213e90606401600060405180830381865afa158015611612573d6000803e3d6000fd5b505050506040513d6000823e601f3d9081017fffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffe01682016040526116589190810190612900565b95945050505050565b73ffffffffffffffffffffffffffffffffffffffff8216600090815260208181526040808320600885901c845290915281205460ff83161c6001165b9392505050565b6000806116d27f00000000000000000000000000000000000000000000000000000000000000008530611f6e565b9050610b05816116e38560016129cb565b60ff16611f97565b60606116f5611f1b565b73ffffffffffffffffffffffffffffffffffffffff1663e8a3d4856040518163ffffffff1660e01b8152600401600060405180830381865afa15801561173f573d6000803e3d6000fd5b505050506040513d6000823e601f3d9081017fffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffe01682016040526117859190810190612900565b905090565b611792611c5d565b63389a75e1600c52806000526020600c2080544211156117ba57636f5e88186000526004601cfd5b60009055610f6b81611e7d565b6117d083611a2c565b60006117dc8760601c90565b905073ffffffffffffffffffffffffffffffffffffffff85163314801590611821575061181f8533601c52670a5a2e7a000000006008526000526030600c205490565b155b15611858576040517fc8e8d39200000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b604080517f0000000000000000000000000000000000000000000000000000000000000000602082015290810188905260ff8716606082015273ffffffffffffffffffffffffffffffffffffffff8616608082015260a081018590526000906118d99060c00160405160208183030381529060405280519060200120612005565b90506118e782828686611ba7565b6118f2898989611be9565b505050505050505050565b611905611c5d565b8060601b61191b57637448fbae6000526004601cfd5b610f6b81611e7d565b61192c611c5d565b7effffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff8111156119565750475b610aae73ffffffffffffffffffffffffffffffffffffffff831682611c41565b60001960601c8281169250838116935081600052837f7d8825530a5a2e7a00000000000000000000000000000000000000000000000017601c52602060002082018201805482169150816119d25763ceea21b66000526004601cfd5b8185148515176119f857816000526030600c20546119f857634b6e7f186000526004601cfd5b6001018390558183827f8c5be1e5ebec7d5bd14f71427d1e84f3dd0314c0f7b2291e5b200ac8c7c3b925600038a450505050565b80421115610f6b576040517f81efbd8d00000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b73ffffffffffffffffffffffffffffffffffffffff8216600090815260208181526040808320909152600883901c825290208054600160ff841681811b9092189283905591901c16610aae576040517f8b190c6300000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b60007f000000000000000000000000000000000000000000000000000000000000000030147f0000000000000000000000000000000000000000000000000000000000000000461416611b63576040517f7d6c03c200000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b67190100000000000060009081527f0000000000000000000000000000000000000000000000000000000000000000601a52603a8381526042601820919052610a29565b611bb3848484846120c8565b611165576040517f8baa579f00000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b6000611bf4836113ee565b5090508015611c2f576040517fddefae2800000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b61116584846101008560ff16176121e7565b60003860003884865af1610aae5763b12d13eb6000526004601cfd5b7fffffffffffffffffffffffffffffffffffffffffffffffffffffffff748739275433146112ce576382b429006000526004601cfd5b6bffffffffffffffffffffffff1661271080821115611cba5763350a88b36000526004601cfd5b8260601b80611cd15763b4457eaa6000526004601cfd5b90911768aa4ec00224afccfdb7555050565b60405163150b7a028082523360208301528560601b60601c604083015283606083015260808083015282518060a08401528015611d2a578060c08401826020870160045afa505b60208360a48301601c860160008a5af1611d4d573d15611d4d573d6000843e3d83fd5b508060e01b825114611d675763d1a57ed66000526004601cfd5b505050505050565b6000611d7a8261120c565b905050600081815273ffffffffffffffffffffffffffffffffffffffff9283167f7d8825530a5a2e7a0000000000000000000000000000000000000000000000008117601c526020909120820182018054919382169182611de35763ceea21b66000526004601cfd5b82600052816001015480861484871417861517611e12576030600c2054611e1257634b6e7f186000526004601cfd5b8015611e2057600083600101555b5082189055601c600c2080547fffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff019055816000827fddf252ad1be2c89b69c2b068fc378daa952ba7f163c4a11628f55a4df523b3ef8238a4505050565b6000611e8c6000612710610ce2565b915050611e998282611c93565b610aae82612287565b8260601b60601c92508160601b60601c91508015159050817f7d8825530a5a2e7a00000000000000000000000000000000000000000000000017601c5282600052806030600c20558060005281837f17307eab39ab6107e8899845ad3d59bd9653f200f220920489ca2b5937696c3160206000a3505050565b60015460009073ffffffffffffffffffffffffffffffffffffffff1680611267576040517fe622d2f600000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b600060405184604052836020528260005260ff600b536055600b20915080604052509392505050565b6000607f8211611fc457826000526094600b5360d6600a5381821560071b17602053506017600a20610a29565b60085b82811c15611fd757600801611fc7565b60031c828152600884901b60005260808101601f536094600a538060d6016009536017016009209392505050565b60007f000000000000000000000000000000000000000000000000000000000000000030147f0000000000000000000000000000000000000000000000000000000000000000461416612084576040517f7d6c03c200000000000000000000000000000000000000000000000000000000815260040160405180910390fd5b67190100000000000060009081527f0000000000000000000000000000000000000000000000000000000000000000601a52603a8381526042601820919052610a29565b73ffffffffffffffffffffffffffffffffffffffff9093169260008415610b055760405184600052604083036121595760208481013560ff81901c601b01825285356040527f7fffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff16606052600160806000825afa805187183d151761215757506000606052604052506001610b05565b505b6041830361219c57604084013560001a602052604084604037602060016080600060015afa805187183d151761219a57506000606052604052506001610b05565b505b600060605280604052631626ba7e60e01b80825285600483015260248201604081528460448401528486606485013760208160648701858b5afa905190911416915050949350505050565b8260601b60601c9250816000527f7d8825530a5a2e7a000000000000000000000000000000000000000000000000601c52828160a01b176020600020830183015582600052601c600c20600181540163ffffffff811685026122585767ea553b3401336cea851560021b526004601cfd5b9055818360007fddf252ad1be2c89b69c2b068fc378daa952ba7f163c4a11628f55a4df523b3ef8138a4505050565b7fffffffffffffffffffffffffffffffffffffffffffffffffffffffff74873927805473ffffffffffffffffffffffffffffffffffffffff9092169182907f8be0079c531659141344cd1fd0a4f28419497f9722a3daafe3b4186f6b6457e0600080a355565b6000602082840312156122ff57600080fd5b81357fffffffff000000000000000000000000000000000000000000000000000000008116811461169d57600080fd5b60005b8381101561234a578181015183820152602001612332565b50506000910152565b602081526000825180602084015261237281604085016020870161232f565b601f017fffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffe0169190910160400192915050565b6000602082840312156123b657600080fd5b5035919050565b803573ffffffffffffffffffffffffffffffffffffffff8116811461126757600080fd5b600080604083850312156123f457600080fd5b6123fd836123bd565b946020939093013593505050565b60008060006060848603121561242057600080fd5b612429846123bd565b9250612437602085016123bd565b9150604084013590509250925092565b6000806040838503121561245a57600080fd5b50508035926020909101359150565b803560ff8116811461126757600080fd5b60008083601f84011261248c57600080fd5b50813567ffffffffffffffff8111156124a457600080fd5b6020830191508360208285010111156124bc57600080fd5b9250929050565b6000806000806000806000806000806101208b8d0312156124e357600080fd5b6124ec8b6123bd565b995060208b0135985061250160408c01612469565b975061250f60608c016123bd565b965060808b0135955061252460a08c016123bd565b945060c08b0135935060e08b013592506101008b013567ffffffffffffffff81111561254f57600080fd5b61255b8d828e0161247a565b915080935050809150509295989b9194979a5092959850565b60006020828403121561258657600080fd5b813561ffff8116811461169d57600080fd5b6000602082840312156125aa57600080fd5b61169d826123bd565b6000806000606084860312156125c857600080fd5b6125d1846123bd565b9250602084013591506125e660408501612469565b90509250925092565b60008060006040848603121561260457600080fd5b83359250602084013567ffffffffffffffff81111561262257600080fd5b61262e8682870161247a565b9497909650939450505050565b6000806040838503121561264e57600080fd5b612657836123bd565b91506020830135801515811461266c57600080fd5b809150509250929050565b60008060008060008060a0878903121561269057600080fd5b612699876123bd565b95506126a7602088016123bd565b94506040870135935060608701359250608087013567ffffffffffffffff8111156126d157600080fd5b6126dd89828a0161247a565b979a9699509497509295939492505050565b60008060008060006080868803121561270757600080fd5b612710866123bd565b945061271e602087016123bd565b935060408601359250606086013567ffffffffffffffff81111561274157600080fd5b61274d8882890161247a565b969995985093965092949392505050565b6000806040838503121561277157600080fd5b8235915061278160208401612469565b90509250929050565b6000806040838503121561279d57600080fd5b6127a6836123bd565b9150612781602084016123bd565b600080600080600080600060c0888a0312156127cf57600080fd5b6127d8886123bd565b9650602088013595506127ed60408901612469565b94506127fb606089016123bd565b93506080880135925060a088013567ffffffffffffffff81111561281e57600080fd5b61282a8a828b0161247a565b989b979a50959850939692959293505050565b7f4e487b7100000000000000000000000000000000000000000000000000000000600052601160045260246000fd5b81810381811115610a2957610a2961283d565b8082028115828204841417610a2957610a2961283d565b6000826128cc577f4e487b7100000000000000000000000000000000000000000000000000000000600052601260045260246000fd5b500490565b7f4e487b7100000000000000000000000000000000000000000000000000000000600052604160045260246000fd5b60006020828403121561291257600080fd5b815167ffffffffffffffff8082111561292a57600080fd5b818401915084601f83011261293e57600080fd5b815181811115612950576129506128d1565b604051601f82017fffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffe0908116603f01168101908382118183101715612996576129966128d1565b816040528281528760208487010111156129af57600080fd5b6129c083602083016020880161232f565b979650505050505050565b60ff8181168382160190811115610a2957610a2961283d56fe546f6b656e697a656420435245415445332056616e69747920416464726573736573a2646970667358221220690362a5663a2c161d75c80136aea497ff2b58cfc6a5e3641c90512208b9847f64736f6c63430008190033546f6b656e697a656420435245415445332056616e69747920416464726573736573000000000000000000000000ea57c1ef7ef1c88b456adf0927ec0eae3b17f1f5
```

## Security

**Known Issues**
- deploy proxies persist post-deployment allowing reuse for other deployments, potentially with
  `msg.value > 0` making it behave incorrectly due to `CALLVALUE` being relied upon for pushing
  zeros: Not seen as an issue because the deploy proxy is only relied upon by the owner upon initial
  deployment, what happens to it afterwards is of little importance
- burning of token upon deployment prevents redeploys on chains that still support classic
  `SELFDESTRUCT`: Not seen as an issue because `SELFDESTRUCT` is considered deprecated regardless
  and because certain second order effects such as the ability to sell no longer usable tokens
  seemed undesirable. Furthermore the complexity required to mitigate the second order effects
  seemed not worth the capability.

