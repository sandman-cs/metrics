# metrics
Generic library for publishing metrics to RabbitMQ

Message Format is JSON:

{
	"app": "testApp",
	"host": "Laptop",
	"level": "info",
	"msg": "Test Message Info",
	"timestamp": "2019-12-14T16:51:45.5573597-06:00",
	"type": "msg",
	"ver": "1.0.0"
}

{
	"app": "testApp",
	"host": "Chief-Laptop",
	"metrics": {
		"default": 20,
		"test0": 1,
		"test1": 1,
		"test10": 1,
		"test11": 1,
		"test12": 1,
		"test13": 1,
		"test14": 1,
		"test15": 1,
		"test16": 1,
		"test17": 1,
		"test18": 1,
		"test19": 1,
		"test2": 1,
		"test3": 1,
		"test4": 1,
		"test5": 1,
		"test6": 1,
		"test7": 1,
		"test8": 1,
		"test9": 1
	},
	"timestamp": "2019-12-14T16:51:45.7678281-06:00",
	"type": "metrics",
	"ver": "1.0.0"
}


<img src="https://github.com/sandman-cs/metrics/blob/master/images/mermaid-diagram-20191214065917.png">


