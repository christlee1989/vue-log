# vue-mobile-log [![Downloads](https://img.shields.io/npm/dm/vue-mobile-log.svg)](https://www.npmjs.com/package/vue-mobile-log) [![Version](https://img.shields.io/npm/v/vue-mobile-log.svg)](https://www.npmjs.com/package/vue-mobile-log) [![License](https://img.shields.io/npm/l/vue-mobile-log.svg)](https://www.npmjs.com/package/vue-mobile-log)

## Screenshot
![](https://github.com/christlee1989/vue-mobile-log/blob/master/screenshot/screenshot.png)  

## Requirements

+ vue@^2.3.0

## Docs

+ 中文文档(建设中)
+ English(working)

## Quick Start

**1.in project path:**
``` bash
npm install vue-mobile-log
```

**2.import:**
``` js
import Vlog from 'vue-mobile-log'
Vue.use(Vlog);
//or
Vue.use(Vlog,options)
```

options:

Parameter | Type | Default | Description
--------- | ---- | ------- | -----------
env | `string` | development | when production does not open the console
level | `string` | debug | debug,info,warn,error

**3.print log:**
```js
//global call:
Vue.$vlog.debug(logMsg);
Vue.$vlog.info(logMsg);
Vue.$vlog.warn(logMsg);
Vue.$vlog.error(logMsg);
 
//in component:
this.$vlog.debug(logMsg);
this.$vlog.info(logMsg);
this.$vlog.warn(logMsg);
this.$vlog.error(logMsg);
```

## Coming...

* in production,log is saved to the client,and sent to the server at some point
* execute code like browser debug console
* more Tag with log for filter
* and more...

## License

MIT

