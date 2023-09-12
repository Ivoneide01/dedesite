(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var m;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function u(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
u("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
u("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ea(aa(this))}})}return a});
function ea(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function fa(a){return a.raw=a}
function ia(a,b){a.raw=b;return a}
function v(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if("number"==typeof a.length)return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function ja(a){if(!(a instanceof Array)){a=v(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function la(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var ma="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)la(d,e)&&(a[e]=d[e])}return a};
u("Object.assign",function(a){return a||ma});
var oa="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},pa=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=oa(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ra;
if("function"==typeof Object.setPrototypeOf)ra=Object.setPrototypeOf;else{var sa;a:{var ta={a:!0},ua={};try{ua.__proto__=ta;sa=ua.a;break a}catch(a){}sa=!1}ra=sa?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var va=ra;
function w(a,b){a.prototype=oa(b.prototype);a.prototype.constructor=a;if(va)va(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Aa=b.prototype}
function wa(){this.s=!1;this.m=null;this.i=void 0;this.h=1;this.G=this.l=0;this.D=this.j=null}
function xa(a){if(a.s)throw new TypeError("Generator is already running");a.s=!0}
wa.prototype.la=function(a){this.i=a};
function ya(a,b){a.j={exception:b,td:!0};a.h=a.l||a.G}
wa.prototype.return=function(a){this.j={return:a};this.h=this.G};
wa.prototype.yield=function(a,b){this.h=b;return{value:a}};
wa.prototype.v=function(a){this.h=a};
function za(a,b,c){a.l=b;void 0!=c&&(a.G=c)}
function Aa(a){a.l=0;var b=a.j.exception;a.j=null;return b}
function Ba(a){var b=a.D.splice(0)[0];(b=a.j=a.j||b)?b.td?a.h=a.l||a.G:void 0!=b.v&&a.G<b.v?(a.h=b.v,a.j=null):a.h=a.G:a.h=0}
function Ca(a){this.h=new wa;this.i=a}
function Da(a,b){xa(a.h);var c=a.h.m;if(c)return Ea(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Fa(a)}
function Ea(a,b,c,d){try{var e=b.call(a.h.m,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.s=!1,e;var f=e.value}catch(g){return a.h.m=null,ya(a.h,g),Fa(a)}a.h.m=null;d.call(a.h,f);return Fa(a)}
function Fa(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.s=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,ya(a.h,c)}a.h.s=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.td)throw b.exception;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ga(a){this.next=function(b){xa(a.h);a.h.m?b=Ea(a,a.h.m.next,b,a.h.la):(a.h.la(b),b=Fa(a));return b};
this.throw=function(b){xa(a.h);a.h.m?b=Ea(a,a.h.m["throw"],b,a.h.la):(ya(a.h,b),b=Fa(a));return b};
this.return=function(b){return Da(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ha(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function A(a){return Ha(new Ga(new Ca(a)))}
function B(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
u("Reflect",function(a){return a?a:{}});
u("Reflect.construct",function(){return pa});
u("Reflect.setPrototypeOf",function(a){return a?a:va?function(b,c){try{return va(b,c),!0}catch(d){return!1}}:null});
u("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.s=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.m()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.m=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(n){k||(k=!0,l.call(h,n))}}
var h=this,k=!1;return{resolve:g(this.W),reject:g(this.m)}};
b.prototype.W=function(g){if(g===this)this.m(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.da(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.S(g):this.G(g)}};
b.prototype.S=function(g){var h=void 0;try{h=g.then}catch(k){this.m(k);return}"function"==typeof h?this.ea(h,g):this.G(g)};
b.prototype.m=function(g){this.la(2,g)};
b.prototype.G=function(g){this.la(1,g)};
b.prototype.la=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.Y();this.D()};
b.prototype.Y=function(){var g=this;e(function(){if(g.R()){var h=da.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.R=function(){if(this.s)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.D=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.da=function(g){var h=this.l();g.Zb(h.resolve,h.reject)};
b.prototype.ea=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(t,p){return"function"==typeof t?function(x){try{l(t(x))}catch(y){n(y)}}:p}
var l,n,r=new b(function(t,p){l=t;n=p});
this.Zb(k(g,l),k(h,n));return r};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Zb=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.s=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=v(g),n=l.next();!n.done;n=l.next())d(n.value).Zb(h,k)})};
b.all=function(g){var h=v(g),k=h.next();return k.done?d([]):new b(function(l,n){function r(x){return function(y){t[x]=y;p--;0==p&&l(t)}}
var t=[],p=0;do t.push(void 0),p++,d(k.value).Zb(r(t.length-1),n),k=h.next();while(!k.done)})};
return b});
u("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=v(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!la(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return l(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),n=new a([[k,2],[l,3]]);if(2!=n.get(k)||3!=n.get(l))return!1;n.delete(k);n.set(l,4);return!n.has(k)&&4==n.get(l)}catch(r){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!la(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&la(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&la(k,g)&&la(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&la(k,g)&&la(k[g],this.h)?delete k[g][this.h]:!1};
return b});
u("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h[1];return ea(function(){if(l){for(;l.head!=h[1];)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var n=h[0][l];if(n&&la(h[0],l))for(h=0;h<n.length;h++){var r=n[h];if(k!==k&&r.key!==r.key||k===r.key)return{id:l,list:n,index:h,entry:r}}return{id:l,list:n,index:-1,entry:void 0}}
function e(h){this[0]={};this[1]=b();this.size=0;if(h){h=v(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(v([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),n=l.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=l.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!l.next().done?!1:!0}catch(r){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this[0][l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this[1],previous:this[1].previous,head:this[1],key:h,value:k},l.list.push(l.entry),this[1].previous.next=l.entry,this[1].previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this[0][h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this[0]={};this[1]=this[1].previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),n;!(n=l.next()).done;)n=n.value,h.call(k,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ja(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
u("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
u("Object.setPrototypeOf",function(a){return a||va});
u("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
u("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
u("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
function Ka(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
u("Array.prototype.keys",function(a){return a?a:function(){return Ka(this,function(b){return b})}});
u("Set",function(a){function b(c){this.h=new Map;if(c){c=v(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(v([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
u("Array.prototype.values",function(a){return a?a:function(){return Ka(this,function(b,c){return c})}});
u("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)la(b,d)&&c.push(b[d]);return c}});
u("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
u("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
u("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ja(this,b,"includes").indexOf(b,c||0)}});
u("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
u("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
u("Array.prototype.entries",function(a){return a?a:function(){return Ka(this,function(b,c){return[b,c]})}});
u("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
u("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
u("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)la(b,d)&&c.push([d,b[d]]);return c}});
u("globalThis",function(a){return a||da});
var La=La||{},C=this||self;function D(a,b,c){a=a.split(".");c=c||C;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function E(a,b){a=a.split(".");b=b||C;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Ma(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Na(a){var b=Ma(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Oa(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Pa(a){return Object.prototype.hasOwnProperty.call(a,Qa)&&a[Qa]||(a[Qa]=++Ra)}
var Qa="closure_uid_"+(1E9*Math.random()>>>0),Ra=0;function Sa(a,b,c){return a.call.apply(a.bind,arguments)}
function Ta(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Ua(a,b,c){Ua=Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Sa:Ta;return Ua.apply(null,arguments)}
function Va(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Wa(){return Date.now()}
function Xa(a,b){function c(){}
c.prototype=b.prototype;a.Aa=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.base=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Ya(a){return a}
;function Za(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,Za);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
Xa(Za,Error);Za.prototype.name="CustomError";function $a(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function ab(){}
function bb(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var cb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},db=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},eb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},fb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},gb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
db(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function hb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function ib(a,b){b=cb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function jb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Na(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function kb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function lb(a){var b=mb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function nb(a){for(var b in a)return!1;return!0}
function ob(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function pb(a){return null!==a&&"privembed"in a?a.privembed:!1}
function qb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function rb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function sb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=sb(a[c]);return b}
var tb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function ub(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<tb.length;f++)c=tb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var vb;function wb(){if(void 0===vb){var a=null,b=C.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Ya,createScript:Ya,createScriptURL:Ya})}catch(c){C.console&&C.console.error(c.message)}vb=a}else vb=a}return vb}
;function xb(){}
function yb(a){return new xb(zb,a)}
var zb={};yb("");var Ab={};function Bb(a){this.h=a}
Bb.prototype.toString=function(){return this.h.toString()};function Cb(a){this.h=a}
Cb.prototype.toString=function(){return this.h+""};
function Db(a){if(a instanceof Cb&&a.constructor===Cb)return a.h;Ma(a);return"type_error:TrustedResourceUrl"}
var Eb={};function Fb(a){var b=wb();a=b?b.createScriptURL(a):a;return new Cb(a,Eb)}
;var Gb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};function Hb(a){this.h=a}
Hb.prototype.toString=function(){return this.h.toString()};
var Ib={},Jb=new Hb("about:invalid#zClosurez",Ib);var Kb,Lb=E("CLOSURE_FLAGS"),Mb=Lb&&Lb[610401301];Kb=null!=Mb?Mb:!1;function Nb(){var a=C.navigator;return a&&(a=a.userAgent)?a:""}
var Ob,Pb=C.navigator;Ob=Pb?Pb.userAgentData||null:null;function Qb(a){return Kb?Ob?Ob.brands.some(function(b){return(b=b.brand)&&-1!=b.indexOf(a)}):!1:!1}
function F(a){return-1!=Nb().indexOf(a)}
;function Rb(){return Kb?!!Ob&&0<Ob.brands.length:!1}
function Sb(){return Rb()?!1:F("Opera")}
function Tb(){return Rb()?!1:F("Trident")||F("MSIE")}
function Ub(){return F("Firefox")||F("FxiOS")}
function Vb(){return Rb()?Qb("Chromium"):(F("Chrome")||F("CriOS"))&&!(Rb()?0:F("Edge"))||F("Silk")}
;function Wb(a){this.h=a}
Wb.prototype.toString=function(){return this.h.toString()};function Xb(){a:{var a=C.document;if(a.querySelector&&(a=a.querySelector("script[nonce]"))&&(a=a.nonce||a.getAttribute("nonce"))&&Yb.test(a))break a;a=""}return a}
var Yb=/^[\w+/_-]+[=]{0,2}$/;function Zb(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var $b=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function ac(a){return a?decodeURI(a):a}
function bc(a,b){return b.match($b)[a]||null}
function cc(a){return ac(bc(3,a))}
function dc(a){var b=a.match($b);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function ec(a){var b=a.indexOf("#");return 0>b?a:a.slice(0,b)}
function fc(a,b){if(!b)return a;var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;return a[0]+(a[1]?"?"+a[1]:"")+a[2]}
function hc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)hc(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function ic(a,b){var c=[];for(b=b||0;b<a.length;b+=2)hc(a[b],a[b+1],c);return c.join("&")}
function jc(a){var b=[],c;for(c in a)hc(c,a[c],b);return b.join("&")}
function kc(a,b){var c=2==arguments.length?ic(arguments[1],0):ic(arguments,1);return fc(a,c)}
function lc(a,b){b=jc(b);return fc(a,b)}
function mc(a,b,c){c=null!=c?"="+encodeURIComponent(String(c)):"";return fc(a,b+c)}
function nc(a,b,c,d){for(var e=c.length;0<=(b=a.indexOf(c,b))&&b<d;){var f=a.charCodeAt(b-1);if(38==f||63==f)if(f=a.charCodeAt(b+e),!f||61==f||38==f||35==f)return b;b+=e+1}return-1}
var oc=/#|$/,pc=/[?&]($|#)/;function qc(a,b){for(var c=a.search(oc),d=0,e,f=[];0<=(e=nc(a,d,b,c));)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(pc,"$1")}
;function rc(a){this.jd=a}
;function sc(a,b,c){this.i=a;this.l=b;this.h=c||[];this.sb=new Map}
m=sc.prototype;m.Ud=function(a){var b=B.apply(1,arguments),c=this.Ec(b);c?c.push(new rc(a)):this.Gd(a,b)};
m.Gd=function(a){var b=this.od(B.apply(1,arguments));this.sb.set(b,[new rc(a)])};
m.Ec=function(){var a=this.od(B.apply(0,arguments));return this.sb.has(a)?this.sb.get(a):void 0};
m.me=function(){var a=this.Ec(B.apply(0,arguments));return a&&a.length?a[0]:void 0};
m.clear=function(){this.sb.clear()};
m.od=function(){var a=B.apply(0,arguments);return a?a.join(","):"key"};function tc(a,b){sc.call(this,a,3,b)}
w(tc,sc);tc.prototype.j=function(a){var b=B.apply(1,arguments),c=0,d=this.me(b);d&&(c=d.jd);this.Gd(c+a,b)};function uc(a,b){sc.call(this,a,2,b)}
w(uc,sc);uc.prototype.record=function(a){this.Ud(a,B.apply(1,arguments))};function vc(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function wc(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Na(d)?wc.apply(null,d):vc(d)}}
;function G(){this.la=this.la;this.G=this.G}
G.prototype.la=!1;G.prototype.Z=function(){return this.la};
G.prototype.dispose=function(){this.la||(this.la=!0,this.M())};
function xc(a,b){yc(a,Va(vc,b))}
function yc(a,b){a.la?b():(a.G||(a.G=[]),a.G.push(b))}
G.prototype.M=function(){if(this.G)for(;this.G.length;)this.G.shift()()};function zc(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
zc.prototype.stopPropagation=function(){this.j=!0};
zc.prototype.preventDefault=function(){this.defaultPrevented=!0};function Ac(a){var b=E("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||C.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Bc(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Cc[c])c=Cc[c];else{c=String(c);if(!Cc[c]){var f=/function\s+([^\(]+)/m.exec(c);Cc[c]=f?f[1]:"[Anonymous]"}c=Cc[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function Bc(a,b){b||(b={});b[Dc(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[Dc(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=Bc(a,b));return c}
function Dc(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var Cc={};var Ec=function(){if(!C.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
C.addEventListener("test",c,b);C.removeEventListener("test",c,b)}catch(d){}return a}();function Fc(){return Kb?!!Ob&&!!Ob.platform:!1}
function Gc(){return F("iPhone")&&!F("iPod")&&!F("iPad")}
;function Hc(a){Hc[" "](a);return a}
Hc[" "]=function(){};var Ic=Sb(),Jc=Tb(),Kc=F("Edge"),Lc=F("Gecko")&&!(-1!=Nb().toLowerCase().indexOf("webkit")&&!F("Edge"))&&!(F("Trident")||F("MSIE"))&&!F("Edge"),Mc=-1!=Nb().toLowerCase().indexOf("webkit")&&!F("Edge");Mc&&F("Mobile");Fc()||F("Macintosh");Fc()||F("Windows");(Fc()?"Linux"===Ob.platform:F("Linux"))||Fc()||F("CrOS");var Nc=C.navigator||null;Nc&&(Nc.appVersion||"").indexOf("X11");var Oc=Fc()?"Android"===Ob.platform:F("Android");Gc();F("iPad");F("iPod");Gc()||F("iPad")||F("iPod");Nb().toLowerCase().indexOf("kaios");
function Pc(){var a=C.document;return a?a.documentMode:void 0}
var Qc;a:{var Rc="",Sc=function(){var a=Nb();if(Lc)return/rv:([^\);]+)(\)|;)/.exec(a);if(Kc)return/Edge\/([\d\.]+)/.exec(a);if(Jc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(Mc)return/WebKit\/(\S+)/.exec(a);if(Ic)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
Sc&&(Rc=Sc?Sc[1]:"");if(Jc){var Tc=Pc();if(null!=Tc&&Tc>parseFloat(Rc)){Qc=String(Tc);break a}}Qc=Rc}var Uc=Qc,Vc;if(C.document&&Jc){var Wc=Pc();Vc=Wc?Wc:parseInt(Uc,10)||void 0}else Vc=void 0;var Xc=Vc;function Yc(a,b){zc.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
Xa(Yc,zc);var Zc={2:"touch",3:"pen",4:"mouse"};
Yc.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(Lc){a:{try{Hc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:Zc[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&Yc.Aa.preventDefault.call(this)};
Yc.prototype.stopPropagation=function(){Yc.Aa.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
Yc.prototype.preventDefault=function(){Yc.Aa.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var $c="closure_listenable_"+(1E6*Math.random()|0);var ad=0;function bd(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.ec=e;this.key=++ad;this.Ub=this.Yb=!1}
function cd(a){a.Ub=!0;a.listener=null;a.proxy=null;a.src=null;a.ec=null}
;function dd(a){this.src=a;this.listeners={};this.h=0}
dd.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=ed(a,b,d,e);-1<g?(b=a[g],c||(b.Yb=!1)):(b=new bd(b,this.src,f,!!d,e),b.Yb=c,a.push(b));return b};
dd.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=ed(e,b,c,d);return-1<b?(cd(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function fd(a,b){var c=b.type;c in a.listeners&&ib(a.listeners[c],b)&&(cd(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function ed(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Ub&&f.listener==b&&f.capture==!!c&&f.ec==d)return e}return-1}
;var gd="closure_lm_"+(1E6*Math.random()|0),hd={},id=0;function jd(a,b,c,d,e){if(d&&d.once)kd(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)jd(a,b[f],c,d,e);else c=ld(c),a&&a[$c]?a.listen(b,c,Oa(d)?!!d.capture:!!d,e):md(a,b,c,!1,d,e)}
function md(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Oa(e)?!!e.capture:!!e,h=nd(a);h||(a[gd]=h=new dd(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=od();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Ec||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(pd(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");id++}}
function od(){function a(c){return b.call(a.src,a.listener,c)}
var b=qd;return a}
function kd(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)kd(a,b[f],c,d,e);else c=ld(c),a&&a[$c]?a.h.add(String(b),c,!0,Oa(d)?!!d.capture:!!d,e):md(a,b,c,!0,d,e)}
function rd(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)rd(a,b[f],c,d,e);else(d=Oa(d)?!!d.capture:!!d,c=ld(c),a&&a[$c])?a.h.remove(String(b),c,d,e):a&&(a=nd(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=ed(b,c,d,e)),(c=-1<a?b[a]:null)&&sd(c))}
function sd(a){if("number"!==typeof a&&a&&!a.Ub){var b=a.src;if(b&&b[$c])fd(b.h,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(pd(c),d):b.addListener&&b.removeListener&&b.removeListener(d);id--;(c=nd(b))?(fd(c,a),0==c.h&&(c.src=null,b[gd]=null)):cd(a)}}}
function pd(a){return a in hd?hd[a]:hd[a]="on"+a}
function qd(a,b){if(a.Ub)a=!0;else{b=new Yc(b,this);var c=a.listener,d=a.ec||a.src;a.Yb&&sd(a);a=c.call(d,b)}return a}
function nd(a){a=a[gd];return a instanceof dd?a:null}
var td="__closure_events_fn_"+(1E9*Math.random()>>>0);function ld(a){if("function"===typeof a)return a;a[td]||(a[td]=function(b){return a.handleEvent(b)});
return a[td]}
;function ud(){G.call(this);this.h=new dd(this);this.Ja=this;this.ea=null}
Xa(ud,G);ud.prototype[$c]=!0;m=ud.prototype;m.addEventListener=function(a,b,c,d){jd(this,a,b,c,d)};
m.removeEventListener=function(a,b,c,d){rd(this,a,b,c,d)};
function vd(a,b){var c=a.ea;if(c){var d=[];for(var e=1;c;c=c.ea)d.push(c),++e}a=a.Ja;c=b.type||b;"string"===typeof b?b=new zc(b,a):b instanceof zc?b.target=b.target||a:(e=b,b=new zc(c,a),ub(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=wd(g,c,!0,b)&&e}b.j||(g=b.h=a,e=wd(g,c,!0,b)&&e,b.j||(e=wd(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=wd(g,c,!1,b)&&e}
m.M=function(){ud.Aa.M.call(this);this.removeAllListeners();this.ea=null};
m.listen=function(a,b,c,d){return this.h.add(String(a),b,!1,c,d)};
m.removeAllListeners=function(a){if(this.h){var b=this.h;a=a&&a.toString();var c=0,d;for(d in b.listeners)if(!a||d==a){for(var e=b.listeners[d],f=0;f<e.length;f++)++c,cd(e[f]);delete b.listeners[d];b.h--}b=c}else b=0;return b};
function wd(a,b,c,d){b=a.h.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Ub&&g.capture==c){var h=g.listener,k=g.ec||g.src;g.Yb&&fd(a.h,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function xd(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
xd.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function yd(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;function zd(a,b){return a+Math.random()*(b-a)}
;function Ad(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
m=Ad.prototype;m.clone=function(){return new Ad(this.x,this.y)};
m.equals=function(a){return a instanceof Ad&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
m.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
m.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
m.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
m.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function Bd(a,b){this.width=a;this.height=b}
m=Bd.prototype;m.clone=function(){return new Bd(this.width,this.height)};
m.aspectRatio=function(){return this.width/this.height};
m.isEmpty=function(){return!(this.width*this.height)};
m.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
m.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
m.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
m.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function Cd(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function Dd(a){var b=document;a=String(a);"application/xhtml+xml"===b.contentType&&(a=a.toLowerCase());return b.createElement(a)}
function Ed(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var Fd;function Gd(){var a=C.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!F("Presto")&&(a=function(){var e=Dd("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Ua(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!Tb()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.hd;c.hd=null;e()}};
return function(e){d.next={hd:e};d=d.next;b.port2.postMessage(0)}}return function(e){C.setTimeout(e,0)}}
;function Hd(a){C.setTimeout(function(){throw a;},0)}
;function Id(){this.i=this.h=null}
Id.prototype.add=function(a,b){var c=Jd.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Id.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Jd=new xd(function(){return new Kd},function(a){return a.reset()});
function Kd(){this.next=this.scope=this.h=null}
Kd.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
Kd.prototype.reset=function(){this.next=this.scope=this.h=null};var Ld,Md=!1,Nd=new Id;function Od(a,b){Ld||Pd();Md||(Ld(),Md=!0);Nd.add(a,b)}
function Pd(){if(C.Promise&&C.Promise.resolve){var a=C.Promise.resolve(void 0);Ld=function(){a.then(Qd)}}else Ld=function(){var b=Qd;
"function"!==typeof C.setImmediate||C.Window&&C.Window.prototype&&(Rb()||!F("Edge"))&&C.Window.prototype.setImmediate==C.setImmediate?(Fd||(Fd=Gd()),Fd(b)):C.setImmediate(b)}}
function Qd(){for(var a;a=Nd.remove();){try{a.h.call(a.scope)}catch(b){Hd(b)}yd(Jd,a)}Md=!1}
;function Rd(a){this.h=0;this.s=void 0;this.l=this.i=this.j=null;this.m=this.G=!1;if(a!=ab)try{var b=this;a.call(void 0,function(c){Sd(b,2,c)},function(c){Sd(b,3,c)})}catch(c){Sd(this,3,c)}}
function Td(){this.next=this.context=this.h=this.i=this.child=null;this.j=!1}
Td.prototype.reset=function(){this.context=this.h=this.i=this.child=null;this.j=!1};
var Ud=new xd(function(){return new Td},function(a){a.reset()});
function Vd(a,b,c){var d=Ud.get();d.i=a;d.h=b;d.context=c;return d}
function Wd(a){if(a instanceof Rd)return a;var b=new Rd(ab);Sd(b,2,a);return b}
function Xd(a){return new Rd(function(b,c){c(a)})}
function Yd(a,b,c){Zd(a,b,c,null)||Od(Va(b,a))}
function $d(a){return new Rd(function(b){var c=a.length,d=[];if(c)for(var e=function(h,k,l){c--;d[h]=k?{fulfilled:!0,value:l}:{fulfilled:!1,reason:l};0==c&&b(d)},f=0,g;f<a.length;f++)g=a[f],Yd(g,Va(e,f,!0),Va(e,f,!1));
else b(d)})}
Rd.prototype.then=function(a,b,c){return ae(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Rd.prototype.$goog_Thenable=!0;m=Rd.prototype;m.uc=function(a,b){return ae(this,null,a,b)};
m.catch=Rd.prototype.uc;m.cancel=function(a){if(0==this.h){var b=new be(a);Od(function(){ce(this,b)},this)}};
function ce(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.child==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?ce(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):de(c),ee(c,e,3,b)))}a.j=null}else Sd(a,3,b)}
function fe(a,b){a.i||2!=a.h&&3!=a.h||ge(a);a.l?a.l.next=b:a.i=b;a.l=b}
function ae(a,b,c,d){var e=Vd(null,null,null);e.child=new Rd(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.h=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof be?g(h):f(k)}catch(l){g(l)}}:g});
e.child.j=a;fe(a,e);return e.child}
m.gf=function(a){this.h=0;Sd(this,2,a)};
m.hf=function(a){this.h=0;Sd(this,3,a)};
function Sd(a,b,c){0==a.h&&(a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself")),a.h=1,Zd(c,a.gf,a.hf,a)||(a.s=c,a.h=b,a.j=null,ge(a),3!=b||c instanceof be||he(a,c)))}
function Zd(a,b,c,d){if(a instanceof Rd)return fe(a,Vd(b||ab,c||null,d)),!0;if(a)try{var e=!!a.$goog_Thenable}catch(g){e=!1}else e=!1;if(e)return a.then(b,c,d),!0;if(Oa(a))try{var f=a.then;if("function"===typeof f)return ie(a,f,b,c,d),!0}catch(g){return c.call(d,g),!0}return!1}
function ie(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function ge(a){a.G||(a.G=!0,Od(a.ge,a))}
function de(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
m.ge=function(){for(var a;a=de(this);)ee(this,a,this.h,this.s);this.G=!1};
function ee(a,b,c,d){if(3==c&&b.h&&!b.j)for(;a&&a.m;a=a.j)a.m=!1;if(b.child)b.child.j=null,je(b,c,d);else try{b.j?b.i.call(b.context):je(b,c,d)}catch(e){ke.call(null,e)}yd(Ud,b)}
function je(a,b,c){2==b?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function he(a,b){a.m=!0;Od(function(){a.m&&ke.call(null,b)})}
var ke=Hd;function be(a){Za.call(this,a)}
Xa(be,Za);be.prototype.name="cancel";function le(a,b){ud.call(this);this.j=a||1;this.i=b||C;this.l=Ua(this.ef,this);this.m=Wa()}
Xa(le,ud);m=le.prototype;m.enabled=!1;m.Fa=null;m.setInterval=function(a){this.j=a;this.Fa&&this.enabled?(this.stop(),this.start()):this.Fa&&this.stop()};
m.ef=function(){if(this.enabled){var a=Wa()-this.m;0<a&&a<.8*this.j?this.Fa=this.i.setTimeout(this.l,this.j-a):(this.Fa&&(this.i.clearTimeout(this.Fa),this.Fa=null),vd(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
m.start=function(){this.enabled=!0;this.Fa||(this.Fa=this.i.setTimeout(this.l,this.j),this.m=Wa())};
m.stop=function(){this.enabled=!1;this.Fa&&(this.i.clearTimeout(this.Fa),this.Fa=null)};
m.M=function(){le.Aa.M.call(this);this.stop();delete this.i};
function me(a,b,c){if("function"===typeof a)c&&(a=Ua(a,c));else if(a&&"function"==typeof a.handleEvent)a=Ua(a.handleEvent,a);else throw Error("Invalid listener argument");return 2147483647<Number(b)?-1:C.setTimeout(a,b||0)}
;function ne(a){G.call(this);this.D=a;this.i=new Map;this.s=new Set;this.j=0;this.l=100;this.flushInterval=3E4;this.h=new le(this.flushInterval);this.h.listen("tick",this.pb,!1,this);xc(this,this.h);this.m=!1}
w(ne,G);m=ne.prototype;m.sendIsolatedPayload=function(a){this.m=a;this.l=1};
function oe(a){a.h.enabled||a.h.start();a.j++;a.j>=a.l&&a.pb()}
m.pb=function(){var a=this.i.values();a=[].concat(ja(a)).filter(function(b){return b.sb.size});
a.length&&this.D.flush(a,this.m);pe(a);this.j=0;this.h.enabled&&this.h.stop()};
m.bd=function(a){var b=B.apply(1,arguments);this.i.has(a)||this.i.set(a,new tc(a,b))};
m.cd=function(a){var b=B.apply(1,arguments);this.i.has(a)||this.i.set(a,new uc(a,b))};
function qe(a,b){return a.s.has(b)?void 0:a.i.get(b)}
m.vc=function(a){this.Sd.apply(this,[a,1].concat(ja(B.apply(1,arguments))))};
m.Sd=function(a,b){var c=B.apply(2,arguments),d=qe(this,a);d&&d instanceof tc&&(d.j(b,c),oe(this))};
m.record=function(a,b){var c=B.apply(2,arguments),d=qe(this,a);d&&d instanceof uc&&(d.record(b,c),oe(this))};
function pe(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function re(a){this.h=a;this.h.bd("/client_streamz/bg/fiec",{vb:3,ub:"rk"},{vb:2,ub:"ec"},{vb:3,ub:"em"})}
function se(a,b,c,d){a.h.vc("/client_streamz/bg/fiec",b,c,d)}
function te(a){this.h=a;this.h.cd("/client_streamz/bg/fil",{vb:3,ub:"rk"})}
te.prototype.record=function(a,b){this.h.record("/client_streamz/bg/fil",a,b)};
function ue(a){this.h=a;this.h.bd("/client_streamz/bg/fsc",{vb:3,ub:"rk"})}
function ve(a){this.h=a;this.h.cd("/client_streamz/bg/fsl",{vb:3,ub:"rk"})}
ve.prototype.record=function(a,b){this.h.record("/client_streamz/bg/fsl",a,b)};var we={toString:function(a){var b=[],c=0;a-=-2147483648;b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ".charAt(a%52);for(a=Math.floor(a/52);0<a;)b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789".charAt(a%62),a=Math.floor(a/62);return b.join("")}};function xe(a){function b(){c-=d;c-=e;c^=e>>>13;d-=e;d-=c;d^=c<<8;e-=c;e-=d;e^=d>>>13;c-=d;c-=e;c^=e>>>12;d-=e;d-=c;d^=c<<16;e-=c;e-=d;e^=d>>>5;c-=d;c-=e;c^=e>>>3;d-=e;d-=c;d^=c<<10;e-=c;e-=d;e^=d>>>15}
a=ye(a);for(var c=2654435769,d=2654435769,e=314159265,f=a.length,g=f,h=0;12<=g;g-=12,h+=12)c+=ze(a,h),d+=ze(a,h+4),e+=ze(a,h+8),b();e+=f;switch(g){case 11:e+=a[h+10]<<24;case 10:e+=a[h+9]<<16;case 9:e+=a[h+8]<<8;case 8:d+=a[h+7]<<24;case 7:d+=a[h+6]<<16;case 6:d+=a[h+5]<<8;case 5:d+=a[h+4];case 4:c+=a[h+3]<<24;case 3:c+=a[h+2]<<16;case 2:c+=a[h+1]<<8;case 1:c+=a[h+0]}b();return we.toString(e)}
function ye(a){for(var b=[],c=0;c<a.length;c++)b.push(a.charCodeAt(c));return b}
function ze(a,b){return a[b+0]+(a[b+1]<<8)+(a[b+2]<<16)+(a[b+3]<<24)}
;Ub();var Ae=Gc()||F("iPod"),Be=F("iPad");!F("Android")||Vb()||Ub()||Sb()||F("Silk");Vb();var Ce=F("Safari")&&!(Vb()||(Rb()?0:F("Coast"))||Sb()||(Rb()?0:F("Edge"))||(Rb()?Qb("Microsoft Edge"):F("Edg/"))||(Rb()?Qb("Opera"):F("OPR"))||Ub()||F("Silk")||F("Android"))&&!(Gc()||F("iPad")||F("iPod"));var De={},Ee=null;function Fe(a,b){Na(a);void 0===b&&(b=0);Ge();b=De[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],l=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+l+g+h+k}l=0;k=d;switch(a.length-e){case 2:l=a[e+1],k=b[(l&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|l>>4]+k+d}return c.join("")}
function He(a){var b=a.length,c=3*b/4;c%3?c=Math.floor(c):-1!="=.".indexOf(a[b-1])&&(c=-1!="=.".indexOf(a[b-2])?c-2:c-1);var d=new Uint8Array(c),e=0;Ie(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function Ie(a,b){function c(k){for(;d<a.length;){var l=a.charAt(d++),n=Ee[l];if(null!=n)return n;if(!/^[\s\xa0]*$/.test(l))throw Error("Unknown base64 encoding at char: "+l);}return k}
Ge();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(64===h&&-1===e)break;b(e<<2|f>>4);64!=g&&(b(f<<4&240|g>>2),64!=h&&b(g<<6&192|h))}}
function Ge(){if(!Ee){Ee={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;5>c;c++){var d=a.concat(b[c].split(""));De[c]=d;for(var e=0;e<d.length;e++){var f=d[e];void 0===Ee[f]&&(Ee[f]=e)}}}}
;var Je="undefined"!==typeof Uint8Array,Ke=!Jc&&"function"===typeof btoa;function Le(a){if(!Ke)return Fe(a);for(var b="",c=0,d=a.length-10240;c<d;)b+=String.fromCharCode.apply(null,a.subarray(c,c+=10240));b+=String.fromCharCode.apply(null,c?a.subarray(c):a);return btoa(b)}
var Me=/[-_.]/g,Ne={"-":"+",_:"/",".":"="};function Oe(a){return Ne[a]||""}
function Pe(a){return Je&&null!=a&&a instanceof Uint8Array}
var Qe={};var Re;function Se(a){if(a!==Qe)throw Error("illegal external caller");}
function Te(a,b){Se(b);this.value_=a;if(null!=a&&0===a.length)throw Error("ByteString should be constructed with non-empty values");}
Te.prototype.isEmpty=function(){return null==this.value_};
Te.prototype.sizeBytes=function(){Se(Qe);var a=this.value_;if(null!=a&&!Pe(a))if("string"===typeof a)if(Ke){Me.test(a)&&(a=a.replace(Me,Oe));a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=He(a);else Ma(a),a=null;return(a=null==a?a:this.value_=a)?a.length:0};function Ue(a){return Array.prototype.slice.call(a)}
;var Ve="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol():void 0;Math.max.apply(Math,ja(Object.values({If:1,Gf:2,Ff:4,Lf:8,Kf:16,Jf:32,yf:64,Mf:128,Ef:256,Df:512,Hf:1024})));var We=Ve?function(a,b){a[Ve]|=b}:function(a,b){void 0!==a.Da?a.Da|=b:Object.defineProperties(a,{Da:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function Xe(a){var b=Ye(a);1!==(b&1)&&(Object.isFrozen(a)&&(a=Ue(a)),Ze(a,b|1))}
var $e=Ve?function(a,b){a[Ve]&=~b}:function(a,b){void 0!==a.Da&&(a.Da&=~b)},Ye=Ve?function(a){return a[Ve]|0}:function(a){return a.Da|0},af=Ve?function(a){return a[Ve]}:function(a){return a.Da},Ze=Ve?function(a,b){a[Ve]=b}:function(a,b){void 0!==a.Da?a.Da=b:Object.defineProperties(a,{Da:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function bf(a,b){Object.isFrozen(a)&&(a=Ue(a));Ze(a,b);return a}
function cf(a){We(a,1);return a}
function df(a,b){Ze(b,(a|0)&-255)}
function ef(a,b){Ze(b,(a|34)&-221)}
function ff(a){a=a>>11&1023;return 0===a?536870912:a}
;var gf={};function hf(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var jf;function kf(a,b){if(null==a){if(!b)throw Error();}else if("string"===typeof a)a=a?new Te(a,Qe):Re||(Re=new Te(null,Qe));else if(a.constructor!==Te)if(Pe(a))a instanceof Uint8Array||Array.isArray(a),a=a.length?new Te(new Uint8Array(a),Qe):Re||(Re=new Te(null,Qe));else throw Error();return a}
var lf,mf=[];Ze(mf,39);lf=Object.freeze(mf);function nf(a){if(a&2)throw Error();}
;function of(a){return a.displayName||a.name||"unknown type name"}
function pf(a){if(null!=a){if("boolean"!==typeof a)throw Error("Expected boolean but got "+Ma(a)+": "+a);a=!!a}return a}
function qf(a){return"number"===typeof a&&Number.isFinite(a)||!!a&&"string"===typeof a&&isFinite(a)}
function rf(a){if(null!=a&&"number"!==typeof a)throw Error();return a}
function sf(a){if(null==a)return a;if("string"===typeof a){if(!a)return;a=+a}if("number"===typeof a)return a}
function tf(a){if(null!=a){if(!qf(a))throw Error("Expected an int64 value encoded as a number or a string but got "+a+" a "+Ma(a));a="string"===typeof a?uf(a):vf(a)}return a}
function vf(a){qf(a);return a}
function uf(a){qf(a);return a}
function wf(a){if("string"!==typeof a)throw Error();return a}
function xf(a){if(null!=a&&"string"!==typeof a)throw Error();return a}
function yf(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+of(b)+" but got "+(a&&of(a.constructor)));}
function zf(a,b,c){var d=!1;if(null!=a&&"object"===typeof a&&!(d=Array.isArray(a))&&a.Oc===gf)return a;if(d){var e=d=Ye(a);0===e&&(e|=c&32);e|=c&2;e!==d&&Ze(a,e);return new b(a)}}
;var Af;function Bf(a,b){Ye(b);Af=b;a=new a(b);Af=void 0;return a}
function Cf(a,b,c){null==a&&(a=Af);Af=void 0;if(null==a){var d=96;c?(a=[c],d|=512):a=[];b&&(d=d&-2095105|(b&1023)<<11)}else{if(!Array.isArray(a))throw Error();d=Ye(a);if(d&64)return a;d|=64;if(c&&(d|=512,c!==a[0]))throw Error();a:{c=a;var e=c.length;if(e){var f=e-1,g=c[f];if(hf(g)){d|=256;b=+!!(d&512)-1;e=f-b;1024<=e&&(Df(c,b,g),e=1023);d=d&-2095105|(e&1023)<<11;break a}}b&&(g=+!!(d&512)-1,b=Math.max(b,e-g),1024<b&&(Df(c,g,{}),d|=256,b=1023),d=d&-2095105|(b&1023)<<11)}}Ze(a,d);return a}
function Df(a,b,c){for(var d=1023+b,e=a.length,f=d;f<e;f++){var g=a[f];null!=g&&g!==c&&(c[f-b]=g)}a.length=d+1;a[d]=c}
;function Ef(a,b){return Ff(b)}
function Ff(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "boolean":return a?1:0;case "object":if(a&&!Array.isArray(a)){if(Pe(a))return Le(a);if(a instanceof Te){var b=a.value_;return null==b?"":"string"===typeof b?b:a.value_=Le(b)}}}return a}
;function Gf(a,b,c){a=Ue(a);var d=a.length,e=b&256?a[d-1]:void 0;d+=e?-1:0;for(b=b&512?1:0;b<d;b++)a[b]=c(a[b]);if(e){b=a[b]={};for(var f in e)b[f]=c(e[f])}return a}
function Hf(a,b,c,d,e,f){if(null!=a){if(Array.isArray(a))a=e&&0==a.length&&Ye(a)&1?void 0:f&&Ye(a)&2?a:If(a,b,c,void 0!==d,e,f);else if(hf(a)){var g={},h;for(h in a)g[h]=Hf(a[h],b,c,d,e,f);a=g}else a=b(a,d);return a}}
function If(a,b,c,d,e,f){var g=d||c?Ye(a):0;d=d?!!(g&32):void 0;a=Ue(a);for(var h=0;h<a.length;h++)a[h]=Hf(a[h],b,c,d,e,f);c&&c(g,a);return a}
function Jf(a){return a.Oc===gf?a.toJSON():Ff(a)}
;function Kf(a,b,c){c=void 0===c?ef:c;if(null!=a){if(Je&&a instanceof Uint8Array)return b?a:new Uint8Array(a);if(Array.isArray(a)){var d=Ye(a);return d&2?a:!b||d&68||!(d&32||0===d)?If(a,Kf,d&4?ef:c,!0,!1,!0):(Ze(a,d|34),a)}a.Oc===gf&&(b=a.A,c=af(b),a=c&2?a:Bf(a.constructor,Lf(b,c,!0)));return a}}
function Lf(a,b,c){var d=c||b&2?ef:df,e=!!(b&32);a=Gf(a,b,function(f){return Kf(f,e,d)});
We(a,32|(c?2:0));return a}
function Mf(a){var b=a.A,c=af(b);return c&2?Bf(a.constructor,Lf(b,c,!1)):a}
;function Nf(a,b){a=a.A;return Of(a,af(a),b)}
function Of(a,b,c,d){if(-1===c)return null;if(c>=ff(b)){if(b&256)return a[a.length-1][c]}else{var e=a.length;if(d&&b&256&&(d=a[e-1][c],null!=d))return d;b=c+(+!!(b&512)-1);if(b<e)return a[b]}}
function J(a,b,c,d){var e=a.A,f=af(e);nf(f);Pf(e,f,b,c,d);return a}
function Pf(a,b,c,d,e){hf(d);var f=ff(b);if(c>=f||e){e=b;if(b&256)f=a[a.length-1];else{if(null==d)return;f=a[f+(+!!(b&512)-1)]={};e|=256}f[c]=d;e!==b&&Ze(a,e)}else a[c+(+!!(b&512)-1)]=d,b&256&&(a=a[a.length-1],c in a&&delete a[c])}
function Qf(a){return void 0!==Rf(a,Sf,11,!1)}
function Tf(a,b,c,d){var e=a.A,f=af(e);nf(f);if(null==c)return Pf(e,f,b),a;if(!(Ye(c)&4)){Object.isFrozen(c)&&(c=Ue(c));for(var g=0;g<c.length;g++)c[g]=d(c[g]);Ze(c,5)}Pf(e,f,b,c);return a}
function Uf(a,b,c,d){a=a.A;var e=af(a);nf(e);for(var f=0,g=0;g<c.length;g++){var h=c[g];null!=Of(a,e,h)&&(0!==f&&Pf(a,e,f),f=h)}(c=f)&&c!==b&&null!=d&&Pf(a,e,c);Pf(a,e,b,d)}
function Rf(a,b,c,d){a=a.A;var e=af(a),f=Of(a,e,c,d);b=zf(f,b,e);b!==f&&null!=b&&Pf(a,e,c,b,d);return b}
function Vf(a,b,c,d){d=void 0===d?!1:d;b=Rf(a,b,c,d);if(null==b)return b;a=a.A;var e=af(a);if(!(e&2)){var f=Mf(b);f!==b&&(b=f,Pf(a,e,c,b,d))}return b}
function Wf(a,b,c,d){null!=d?yf(d,b):d=void 0;return J(a,c,d)}
function Xf(a,b,c,d){var e=a.A,f=af(e);nf(f);if(null!=d){for(var g=!!d.length,h=0;h<d.length;h++){var k=d[h];yf(k,b);g=g&&!(Ye(k.A)&2)}b=Ye(d);h=b|1;h=(g?h|8:h&-9)|4;h!=b&&(d=bf(d,h))}null==d&&(d=void 0);Pf(e,f,c,d);return a}
function Yf(a,b){a=Nf(a,b);var c;null==a?c=a:qf(a)?"number"===typeof a?c=vf(a):c=uf(a):c=void 0;return c}
function Zf(a){a=Nf(a,1);a=null==a?a:qf(a)?"string"===typeof a?uf(a):vf(a):void 0;return a}
function $f(a){return kf(a,!1)}
function ag(){var a=new bg;return J(a,1,1)}
;function cg(a,b,c){this.A=Cf(a,b,c)}
m=cg.prototype;m.toJSON=function(){if(jf)var a=dg(this,this.A,!1);else a=If(this.A,Jf,void 0,void 0,!1,!1),a=dg(this,a,!0);return a};
m.serialize=function(){jf=!0;try{return JSON.stringify(this.toJSON(),Ef)}finally{jf=!1}};
m.clone=function(){var a=this.A,b=af(a);return Bf(this.constructor,Lf(a,b,!1))};
m.Oc=gf;m.toString=function(){return dg(this,this.A,!1).toString()};
function dg(a,b,c){var d=a.constructor.Wa,e=af(c?a.A:b),f=ff(e);e=!1;if(d){if(!c){b=Ue(b);var g;if(b.length&&hf(g=b[b.length-1]))for(e=0;e<d.length;e++)if(d[e]>=f){Object.assign(b[b.length-1]={},g);break}e=!0}g=b;c=!c;f=af(a.A);a=ff(f);f=+!!(f&512)-1;for(var h,k,l=0;l<d.length;l++)if(k=d[l],k<a){k+=f;var n=g[k];null==n?g[k]=c?lf:cf([]):c&&n!==lf&&Xe(n)}else h||(n=void 0,g.length&&hf(n=g[g.length-1])?h=n:g.push(h={})),n=h[k],null==h[k]?h[k]=c?lf:cf([]):c&&n!==lf&&Xe(n)}d=b.length;if(!d)return b;var r;
if(hf(h=b[d-1])){a:{var t=h;g={};c=!1;for(var p in t)a=t[p],Array.isArray(a)&&a!=a&&(c=!0),null!=a?g[p]=a:c=!0;if(c){for(var x in g){t=g;break a}t=null}}t!=h&&(r=!0);d--}for(;0<d;d--){h=b[d-1];if(null!=h)break;var y=!0}if(!r&&!y)return b;var z;e?z=b:z=Array.prototype.slice.call(b,0,d);b=z;e&&(b.length=d);t&&b.push(t);return b}
;function eg(a){this.A=Cf(a)}
w(eg,cg);var fg=[1,2,3];function gg(a){this.A=Cf(a)}
w(gg,cg);var hg=[1,2,3];function ig(a){this.A=Cf(a)}
w(ig,cg);ig.Wa=[1];function jg(a){this.A=Cf(a)}
w(jg,cg);jg.Wa=[3,6,4];function kg(a){this.A=Cf(a)}
w(kg,cg);kg.Wa=[1];function lg(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.startsWith("blob:")&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==
c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function mg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=l=0}
function b(r){for(var t=g,p=0;64>p;p+=4)t[p/4]=r[p]<<24|r[p+1]<<16|r[p+2]<<8|r[p+3];for(p=16;80>p;p++)r=t[p-3]^t[p-8]^t[p-14]^t[p-16],t[p]=(r<<1|r>>>31)&4294967295;r=e[0];var x=e[1],y=e[2],z=e[3],H=e[4];for(p=0;80>p;p++){if(40>p)if(20>p){var I=z^x&(y^z);var M=1518500249}else I=x^y^z,M=1859775393;else 60>p?(I=x&y|z&(x|y),M=2400959708):(I=x^y^z,M=3395469782);I=((r<<5|r>>>27)&4294967295)+I+H+M+t[p]&4294967295;H=z;z=y;y=(x<<30|x>>>2)&4294967295;x=r;r=I}e[0]=e[0]+r&4294967295;e[1]=e[1]+x&4294967295;e[2]=
e[2]+y&4294967295;e[3]=e[3]+z&4294967295;e[4]=e[4]+H&4294967295}
function c(r,t){if("string"===typeof r){r=unescape(encodeURIComponent(r));for(var p=[],x=0,y=r.length;x<y;++x)p.push(r.charCodeAt(x));r=p}t||(t=r.length);p=0;if(0==l)for(;p+64<t;)b(r.slice(p,p+64)),p+=64,n+=64;for(;p<t;)if(f[l++]=r[p++],n++,64==l)for(l=0,b(f);p+64<t;)b(r.slice(p,p+64)),p+=64,n+=64}
function d(){var r=[],t=8*n;56>l?c(h,56-l):c(h,64-(l-56));for(var p=63;56<=p;p--)f[p]=t&255,t>>>=8;b(f);for(p=t=0;5>p;p++)for(var x=24;0<=x;x-=8)r[t++]=e[p]>>x&255;return r}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,n;a();return{reset:a,update:c,digest:d,be:function(){for(var r=d(),t="",p=0;p<r.length;p++)t+="0123456789ABCDEF".charAt(Math.floor(r[p]/16))+"0123456789ABCDEF".charAt(r[p]%16);return t}}}
;function ng(a,b,c){var d=String(C.location.href);return d&&a&&b?[b,og(lg(d),a,c||null)].join(" "):null}
function og(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],db(d,function(h){e.push(h)}),pg(e.join(" "));
var f=[],g=[];db(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];db(d,function(h){e.push(h)});
a=pg(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function pg(a){var b=mg();b.update(a);return b.be().toLowerCase()}
;var qg={};function rg(a){this.h=a||{cookie:""}}
m=rg.prototype;m.isEnabled=function(){if(!C.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{ic:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
m.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.eg;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.ic}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
m.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Gb(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
m.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{ic:0,path:b,domain:c});return d};
m.Hc=function(){return sg(this).keys};
m.isEmpty=function(){return!this.h.cookie};
m.clear=function(){for(var a=sg(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function sg(a){a=(a.h.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Gb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var tg=new rg("undefined"==typeof document?null:document);function ug(a){return!!qg.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function vg(a){a=void 0===a?!1:a;var b=C.__SAPISID||C.__APISID||C.__3PSAPISID||C.__OVERRIDE_SID;ug(a)&&(b=b||C.__1PSAPISID);if(b)return!0;if("undefined"!==typeof document){var c=new rg(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID")||c.get("OSID");ug(a)&&(b=b||c.get("__Secure-1PAPISID"))}return!!b}
function wg(a,b,c,d){(a=C[a])||"undefined"===typeof document||(a=(new rg(document)).get(b));return a?ng(a,c,d):null}
function xg(a,b){b=void 0===b?!1:b;var c=lg(String(C.location.href)),d=[];if(vg(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?C.__SAPISID:C.__APISID;e||"undefined"===typeof document||(e=new rg(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?ng(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&ug(b)&&((b=wg("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=wg("__3PSAPISID","__Secure-3PAPISID",
"SAPISID3PHASH",a))&&d.push(a))}return 0==d.length?null:d.join(" ")}
;function yg(a){this.A=Cf(a)}
w(yg,cg);yg.Wa=[2];function zg(a){this.A=Cf(a)}
w(zg,cg);function Ag(a){this.A=Cf(a)}
w(Ag,cg);function Bg(a){this.h=this.i=this.j=a}
Bg.prototype.reset=function(){this.h=this.i=this.j};
Bg.prototype.getValue=function(){return this.i};function Cg(a){this.A=Cf(a)}
w(Cg,cg);function Dg(a){this.A=Cf(a)}
w(Dg,cg);Dg.Wa=[1];function Sf(a){this.A=Cf(a)}
w(Sf,cg);var Eg=["platform","platformVersion","architecture","model","uaFullVersion"];new Dg;function bg(a){this.A=Cf(a)}
w(bg,cg);function Fg(a){this.A=Cf(a)}
w(Fg,cg);function Gg(a){this.A=Cf(a,34)}
w(Gg,cg);Gg.Wa=[3,20,27];function Hg(a){this.A=Cf(a,19)}
w(Hg,cg);Hg.Wa=[3,5];function Ig(a){this.A=Cf(a,6)}
w(Ig,cg);var Kg=function(a){return function(b){if(null==b||""==b)b=new a;else{b=JSON.parse(b);if(!Array.isArray(b))throw Error(void 0);We(b,32);b=Bf(a,b)}return b}}(Ig);
Ig.Wa=[5];function Lg(a){this.A=Cf(a)}
w(Lg,cg);var Mg;Mg=new function(a,b,c){this.h=a;this.fieldName=b;this.ctor=c;this.isRepeated=0;this.i=Vf;this.defaultValue=void 0}(175237375,{Vf:0},Lg);function Ng(a){G.call(this);var b=this;this.componentId="";this.i=[];this.na="";this.Ba=this.ea=-1;this.ma=!1;this.D=this.experimentIds=null;this.Y=this.da=this.s=this.l=0;this.Ja=1;this.timeoutMillis=0;this.R=!1;this.logSource=a.logSource;this.wb=a.wb||function(){};
this.j=new Og(a.logSource,a.Ab);this.network=a.network;this.Hb=a.Hb||null;this.bufferSize=1E3;this.qb=Va(zd,0,1);this.W=a.jf||null;this.sessionIndex=a.sessionIndex||null;this.Ob=a.Ob||!1;this.pageId=a.pageId||null;this.logger=null;this.withCredentials=!a.ld;this.Ab=a.Ab||!1;var c=ag();Pg(this.j,c);this.m=new Bg(1E4);this.h=new le(this.m.getValue());xc(this,this.h);a=Qg(this,a.dd);jd(this.h,"tick",a,!1,this);this.S=new le(6E5);xc(this,this.S);jd(this.S,"tick",a,!1,this);this.Ob||this.S.start();this.Ab||
(jd(document,"visibilitychange",function(){"hidden"===document.visibilityState&&b.Cc()}),jd(document,"pagehide",this.Cc,!1,this))}
w(Ng,G);function Qg(a,b){return b?function(){b().then(function(){a.flush()})}:function(){a.flush()}}
m=Ng.prototype;m.M=function(){this.Cc();G.prototype.M.call(this)};
function Rg(a){a.W||(a.W=.01>a.qb()?"https://www.google.com/log?format=json&hasfast=true":"https://play.google.com/log?format=json&hasfast=true");return a.W}
function Sg(a,b){a.m=new Bg(1>b?1:b);a.h.setInterval(a.m.getValue())}
m.log=function(a){a=a.clone();var b=this.Ja++;a=J(a,21,tf(b));this.componentId&&J(a,26,xf(this.componentId));if(!Zf(a)){b=a;var c=Date.now().toString();J(b,1,tf(c))}null==Yf(a,15)&&J(a,15,tf(60*(new Date).getTimezoneOffset()));this.experimentIds&&(b=this.experimentIds.clone(),Wf(a,yg,16,b));b=this.i.length-this.bufferSize+1;0<b&&(this.i.splice(0,b),this.l+=b);this.i.push(a);this.Ob||this.h.enabled||this.h.start()};
m.flush=function(a,b){var c=this;if(0===this.i.length)a&&a();else if(this.R)Tg(this.j,3),Ug(this);else{var d=Date.now();if(this.Ba>d&&this.ea<d)b&&b("throttled");else{Tg(this.j,1);var e=Vg(this.j,this.i,this.l,this.s,this.Hb,this.da,this.Y);d={};var f=this.wb();f&&(d.Authorization=f);var g=Rg(this);this.sessionIndex&&(d["X-Goog-AuthUser"]=this.sessionIndex,g=mc(g,"authuser",this.sessionIndex));this.pageId&&(d["X-Goog-PageId"]=this.pageId,g=mc(g,"pageId",this.pageId));if(f&&this.na===f)b&&b("stale-auth-token");
else{this.i=[];this.h.enabled&&this.h.stop();this.l=0;var h=e.serialize(),k;this.D&&this.D.isSupported(h.length)&&(k=this.D.compress(h));var l={url:g,body:h,Yd:1,Sc:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},n=function(p){c.m.reset();c.h.setInterval(c.m.getValue());if(p){var x=null;try{var y=JSON.stringify(JSON.parse(p.replace(")]}'\n","")));x=Kg(y)}catch(H){}if(x){p=Number;y="-1";y=void 0===y?"0":y;var z=Zf(x);p=p(null!=z?z:y);0<p&&(c.ea=Date.now(),
c.Ba=c.ea+p);x=Mg.ctor?Mg.i(x,Mg.ctor,Mg.h,!0):Mg.i(x,Mg.h,null,!0);if(p=null===x?void 0:x)x=-1,x=void 0===x?0:x,p=sf(Nf(p,1)),x=null!=p?p:x,-1!==x&&(c.ma||Sg(c,x))}}a&&a();c.s=0},r=function(p,x){var y=e.A,z=af(y),H=!!(z&2);
var I=H?1:2,M=!!(z&2);var N=z&2;var K=Of(y,z,3);Array.isArray(K)||(K=lf);var V=Ye(K);V&1||cf(K);N?V&2||We(K,34):V&32&&!(V&2)&&$e(K,32);N=K;if(N!==lf&&Ye(N)&4)3!==I&&(M?2===I&&(I=Ye(N),N=Ue(N),Ze(N,I),Pf(y,z,3,N)):(M=Object.isFrozen(N),1===I?M||Object.freeze(N):(I=Ye(N),K=I&-35,M&&(N=Ue(N),I=0,Pf(y,z,3,N)),I!==K&&Ze(N,K)))),y=N;else{K=N;N=!!(z&2);var Z=!!(Ye(K)&2);M=K;!N&&Z&&(K=Ue(K));V=z|(Z?2:0);Z=Z||void 0;for(var ha=0,qa=0;ha<K.length;ha++){var na=zf(K[ha],Gg,V);void 0!==na&&(Z=Z||af(na.A)&2,K[qa++]=
na)}qa<ha&&(K.length=qa);Z=!Z;V=Ye(K);ha=V|5;Z=Z?ha|8:ha&-9;V!=Z&&(K=bf(K,Z));M!==K&&Pf(y,z,3,K);(N&&2!==I||1===I)&&Object.freeze(K);y=K}if(!(H||Ye(y)&8)){for(H=0;H<y.length;H++)z=y[H],I=Mf(z),z!==I&&(y[H]=I);We(y,8)}H=Yf(e,14);z=c.m;z.h=Math.min(3E5,2*z.h);z.i=Math.min(3E5,z.h+Math.round(.2*(Math.random()-.5)*z.h));c.h.setInterval(c.m.getValue());401===p&&f&&(c.na=f);H&&(c.l+=H);void 0===x&&(x=c.isRetryable(p));x&&(c.i=y.concat(c.i),c.Ob||c.h.enabled||c.h.start());b&&b("net-send-failed",p);++c.s},
t=function(){c.network&&c.network.send(l,n,r)};
k?k.then(function(p){l.Sc["Content-Encoding"]="gzip";l.Sc["Content-Type"]="application/binary";l.body=p;l.Yd=2;t()},function(){t()}):t()}}}};
m.Cc=function(){Wg(this.j,!0);this.flush();Wg(this.j,!1)};
function Ug(a){Xg(a,function(b,c){b=mc(b,"format","json");var d=!1;try{d=window.navigator.sendBeacon(b,c.serialize())}catch(e){}a.R&&!d&&(a.R=!1);return d})}
function Xg(a,b){if(0!==a.i.length){var c=qc(Rg(a),"format");c=kc(c,"auth",a.wb(),"authuser",a.sessionIndex||"0");for(var d=0;10>d&&a.i.length;++d){var e=a.i.slice(0,32),f=Vg(a.j,e,a.l,a.s,a.Hb,a.da,a.Y);if(!b(c,f)){++a.s;break}a.l=0;a.s=0;a.da=0;a.Y=0;a.i=a.i.slice(e.length)}a.h.enabled&&a.h.stop()}}
m.isRetryable=function(a){return 500<=a&&600>a||401===a||0===a};
function Og(a,b){this.Ab=b=void 0===b?!1:b;this.uach=this.locale=null;this.h=new Hg;Number.isInteger(a)&&J(this.h,2,a);b||(this.locale=document.documentElement.getAttribute("lang"));Pg(this,new bg)}
function Pg(a,b){Wf(a.h,bg,1,b);Nf(b,1)||J(b,1,1);if(!a.Ab){b=Yg(a);var c=Nf(b,5);(null==c||"string"===typeof c)&&c||J(b,5,xf(a.locale))}a.uach&&(b=Yg(a),Vf(b,Dg,9)||Wf(b,Dg,9,a.uach))}
function Tg(a,b){Qf(Zg(a))&&(a=$g(a),J(a,1,b))}
function Wg(a,b){Qf(Zg(a))&&(a=$g(a),J(a,2,pf(b)))}
function Zg(a){return Vf(a.h,bg,1)}
function ah(a,b){var c=void 0===c?Eg:c;b(window,c).then(function(d){a.uach=d;d=Yg(a);Wf(d,Dg,9,a.uach);return!0}).catch(function(){return!1})}
function Yg(a){a=Zg(a);var b=Vf(a,Sf,11);b||(b=new Sf,Wf(a,Sf,11,b));return b}
function $g(a){a=Yg(a);var b=Vf(a,Cg,10);b||(b=new Cg,J(b,2,pf(!1)),Wf(a,Cg,10,b));return b}
function Vg(a,b,c,d,e,f,g){c=void 0===c?0:c;f=void 0===f?0:f;g=void 0===g?0:g;d=void 0===d?0:d;if(Qf(Zg(a))){var h=$g(a);J(h,3,rf(d))}Qf(Zg(a))&&(d=$g(a),J(d,4,rf(f)));Qf(Zg(a))&&(f=$g(a),J(f,5,rf(g)));a=a.h.clone();g=Date.now().toString();a=J(a,4,tf(g));b=Xf(a,Gg,3,b);e&&(a=new zg,e=J(a,13,rf(e)),a=new Ag,e=Wf(a,zg,2,e),a=new Fg,e=Wf(a,Ag,1,e),Wf(b,Fg,18,e));c&&J(b,14,tf(c));return b}
;function bh(){}
bh.prototype.serialize=function(a){var b=[];ch(this,a,b);return b.join("")};
function ch(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),ch(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),dh(d,c),c.push(":"),ch(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":dh(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var eh={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},fh=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function dh(a,b){b.push('"',a.replace(fh,function(c){var d=eh[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),eh[c]=d);return d}),'"')}
;function gh(){}
gh.prototype.h=null;gh.prototype.getOptions=function(){var a;(a=this.h)||(a={},hh(this)&&(a[0]=!0,a[1]=!0),a=this.h=a);return a};var ih;function jh(){}
Xa(jh,gh);function kh(a){return(a=hh(a))?new ActiveXObject(a):new XMLHttpRequest}
function hh(a){if(!a.i&&"undefined"==typeof XMLHttpRequest&&"undefined"!=typeof ActiveXObject){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++){var d=b[c];try{return new ActiveXObject(d),a.i=d}catch(e){}}throw Error("Could not create ActiveXObject. ActiveX might be disabled, or MSXML might not be installed");}return a.i}
ih=new jh;function lh(a){ud.call(this);this.headers=new Map;this.S=a||null;this.i=!1;this.R=this.I=null;this.l=this.da="";this.j=this.Y=this.s=this.W=!1;this.m=0;this.D=null;this.Ba="";this.ma=this.na=!1}
Xa(lh,ud);var mh=/^https?$/i,nh=["POST","PUT"],oh=[];function ph(a,b,c,d,e,f,g){var h=new lh;oh.push(h);b&&h.listen("complete",b);h.h.add("ready",h.ae,!0,void 0,void 0);f&&(h.m=Math.max(0,f));g&&(h.na=g);h.send(a,c,d,e)}
m=lh.prototype;m.ae=function(){this.dispose();ib(oh,this)};
m.send=function(a,b,c,d){if(this.I)throw Error("[goog.net.XhrIo] Object is active with another request="+this.da+"; newUri="+a);b=b?b.toUpperCase():"GET";this.da=a;this.l="";this.W=!1;this.i=!0;this.I=this.S?kh(this.S):kh(ih);this.R=this.S?this.S.getOptions():ih.getOptions();this.I.onreadystatechange=Ua(this.xd,this);try{this.getStatus(),this.Y=!0,this.I.open(b,String(a),!0),this.Y=!1}catch(g){this.getStatus();qh(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,
d[e]);else if("function"===typeof d.keys&&"function"===typeof d.get){e=v(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=C.FormData&&a instanceof C.FormData;!(0<=cb(nh,b))||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=v(c);for(d=b.next();!d.done;d=b.next())c=v(d.value),d=c.next().value,c=c.next().value,this.I.setRequestHeader(d,c);this.Ba&&(this.I.responseType=this.Ba);"withCredentials"in this.I&&this.I.withCredentials!==this.na&&(this.I.withCredentials=this.na);try{rh(this),0<this.m&&(this.ma=sh(this.I),this.getStatus(),this.ma?(this.I.timeout=this.m,this.I.ontimeout=Ua(this.Ld,
this)):this.D=me(this.Ld,this.m,this)),this.getStatus(),this.s=!0,this.I.send(a),this.s=!1}catch(g){this.getStatus(),qh(this,g)}};
function sh(a){return Jc&&"number"===typeof a.timeout&&void 0!==a.ontimeout}
m.Ld=function(){"undefined"!=typeof La&&this.I&&(this.l="Timed out after "+this.m+"ms, aborting",this.getStatus(),vd(this,"timeout"),this.abort(8))};
function qh(a,b){a.i=!1;a.I&&(a.j=!0,a.I.abort(),a.j=!1);a.l=b;th(a);uh(a)}
function th(a){a.W||(a.W=!0,vd(a,"complete"),vd(a,"error"))}
m.abort=function(){this.I&&this.i&&(this.getStatus(),this.i=!1,this.j=!0,this.I.abort(),this.j=!1,vd(this,"complete"),vd(this,"abort"),uh(this))};
m.M=function(){this.I&&(this.i&&(this.i=!1,this.j=!0,this.I.abort(),this.j=!1),uh(this,!0));lh.Aa.M.call(this)};
m.xd=function(){this.Z()||(this.Y||this.s||this.j?vh(this):this.Fe())};
m.Fe=function(){vh(this)};
function vh(a){if(a.i&&"undefined"!=typeof La)if(a.R[1]&&4==wh(a)&&2==a.getStatus())a.getStatus();else if(a.s&&4==wh(a))me(a.xd,0,a);else if(vd(a,"readystatechange"),a.isComplete()){a.getStatus();a.i=!1;try{if(xh(a))vd(a,"complete"),vd(a,"success");else{try{var b=2<wh(a)?a.I.statusText:""}catch(c){b=""}a.l=b+" ["+a.getStatus()+"]";th(a)}}finally{uh(a)}}}
function uh(a,b){if(a.I){rh(a);var c=a.I,d=a.R[0]?function(){}:null;
a.I=null;a.R=null;b||vd(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function rh(a){a.I&&a.ma&&(a.I.ontimeout=null);a.D&&(C.clearTimeout(a.D),a.D=null)}
m.isActive=function(){return!!this.I};
m.isComplete=function(){return 4==wh(this)};
function xh(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=0===b)a=bc(1,String(a.da)),!a&&C.self&&C.self.location&&(a=C.self.location.protocol.slice(0,-1)),b=!mh.test(a?a.toLowerCase():"");c=b}return c}
function wh(a){return a.I?a.I.readyState:0}
m.getStatus=function(){try{return 2<wh(this)?this.I.status:-1}catch(a){return-1}};
m.getLastError=function(){return"string"===typeof this.l?this.l:String(this.l)};function yh(){}
yh.prototype.send=function(a,b,c){b=void 0===b?function(){}:b;
c=void 0===c?function(){}:c;
ph(a.url,function(d){d=d.target;if(xh(d)){try{var e=d.I?d.I.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Sc,a.timeoutMillis,a.withCredentials)};function zh(a,b){G.call(this);this.logSource=a;this.sessionIndex=b;this.i="https://play.google.com/log?format=json&hasfast=true";this.j=!1;this.componentId="";this.network=new yh}
w(zh,G);zh.prototype.ld=function(){this.W=!0;return this};function Ah(a,b,c,d,e,f){a=void 0===a?-1:a;b=void 0===b?"":b;c=void 0===c?"":c;d=void 0===d?!1:d;e=void 0===e?"":e;G.call(this);f?a=f:(a=new zh(a,"0"),a.componentId=b,xc(this,a),""!=c&&(a.i=c),d&&(a.j=!0),e&&(a.h=e),b=new Ng({logSource:a.logSource,wb:a.wb?a.wb:xg,sessionIndex:a.sessionIndex,jf:a.i,Ab:a.j,Ob:!1,ld:a.W,pageId:a.pageId,dd:a.dd,network:a.network?a.network:void 0}),xc(a,b),a.s&&Pg(b.j,a.s),a.h&&(c=a.h,d=Yg(b.j),J(d,7,xf(c))),a.m&&(b.D=a.m),a.componentId&&(b.componentId=a.componentId),
a.Hb&&(b.Hb=a.Hb),a.l&&((c=a.l)?(b.experimentIds||(b.experimentIds=new yg),c=c.serialize(),J(b.experimentIds,4,xf(c))):b.experimentIds&&J(b.experimentIds,4,void 0,!1)),a.R&&(c=a.R,b.experimentIds||(b.experimentIds=new yg),Tf(b.experimentIds,2,c,$f)),a.D&&(c=a.D,b.ma=!0,Sg(b,c)),a.S&&ah(b.j,a.S),a=b);this.h=a}
w(Ah,G);
Ah.prototype.flush=function(a){var b=a||[];if(b.length){a=new kg;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=e;var g=new jg;g=J(g,1,xf(f.i));for(var h=f,k=[],l=0;l<h.h.length;l++)k.push(h.h[l].ub);g=Tf(g,3,k,wf);h=[];k=[];l=v(f.sb.keys());for(var n=l.next();!n.done;n=l.next())k.push(n.value.split(","));for(l=0;l<k.length;l++){n=k[l];var r=f.l;for(var t=f.Ec(n)||[],p=[],x=0;x<t.length;x++){var y=t[x],z=y&&y.jd;y=new gg;switch(r){case 3:var H=Number(z);Number.isFinite(H)&&Uf(y,1,hg,tf(H));break;case 2:H=
y;z=Number(z);if(null!=z&&"number"!==typeof z)throw Error("Value of float/double field must be a number, found "+typeof z+": "+z);Uf(H,2,hg,z)}p.push(y)}r=p;for(t=0;t<r.length;t++){p=r[t];x=new ig;p=Wf(x,gg,2,p);x=n;y=[];H=f;z=[];for(var I=0;I<H.h.length;I++)z.push(H.h[I].vb);H=z;for(z=0;z<H.length;z++){var M=H[z],N=x[z];I=new eg;switch(M){case 3:Uf(I,1,fg,xf(String(N)));break;case 2:M=Number(N);Number.isFinite(M)&&Uf(I,2,fg,rf(M));break;case 1:Uf(I,3,fg,pf("true"==N))}y.push(I)}Xf(p,eg,1,y);h.push(p)}}Xf(g,
ig,4,h);c.push(g);e.clear()}Xf(a,jg,1,c);b=this.h;a instanceof Gg?b.log(a):(c=new Gg,a=a.serialize(),a=J(c,8,xf(a)),b.log(a));this.h.flush()}};function Bh(a){this.s=Ch();this.m=new Ah(1828);this.h=new ne(this.m);this.G=new te(this.h);this.j=new ue(this.h);this.l=new ve(this.h);this.i=new re(this.h);this.Qa=xe(a)}
function Ch(){var a,b,c;return null!=(c=null==(a=globalThis.performance)?void 0:null==(b=a.now)?void 0:b.call(a))?c:Date.now()}
;function Dh(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function Eh(a){function b(p,x){Promise.resolve().then(function(){var y;null!=(y=c.va)&&y.G.record(Ch()-y.s,y.Qa);g.resolve({Wd:p,af:x})})}
var c=this;this.h=!1;var d=a.program;var e=a.oe;if(!1!==a.Ke){var f;this.va=null!=(f=a.va)?f:new Bh(e)}var g=new Dh;this.i=g.promise;if(!C[e]){var h;null!=(h=this.va)&&se(h.i,h.Qa,1,"");var k;null!=(k=this.va)&&k.h.pb()}else if(!C[e].a){var l;null!=(l=this.va)&&se(l.i,l.Qa,2,"");var n;null!=(n=this.va)&&n.h.pb()}try{this.j=v((0,C[e].a)(d,b,!0,a.lg)).next().value,this.Ze=g.promise.then(function(){})}catch(p){var r;
null!=(r=this.va)&&se(r.i,r.Qa,4,p.message);var t;null!=(t=this.va)&&t.h.pb();throw p;}}
Eh.prototype.snapshot=function(a){var b=this;if(this.h)throw Error("Already disposed");var c=Ch(),d;null!=(d=this.va)&&d.j.h.vc("/client_streamz/bg/fsc",d.Qa);return this.i.then(function(e){var f=e.Wd;return new Promise(function(g){f(function(h){var k;null!=(k=b.va)&&k.l.record(Ch()-c,k.Qa);g(h)},[a.kd,
a.bf,a.lf])})})};
Eh.prototype.Id=function(a){if(this.h)throw Error("Already disposed");var b=Ch(),c;null!=(c=this.va)&&c.j.h.vc("/client_streamz/bg/fsc",c.Qa);a=this.j([a.kd,a.bf,a.lf]);var d;null!=(d=this.va)&&d.l.record(Ch()-b,d.Qa);return a};
Eh.prototype.dispose=function(){var a;null!=(a=this.va)&&a.h.pb();this.h=!0;this.i.then(function(b){(b=b.af)&&b()})};
Eh.prototype.Z=function(){return this.h};var Fh=window;yb("csi.gstatic.com");yb("googleads.g.doubleclick.net");yb("partner.googleadservices.com");yb("pubads.g.doubleclick.net");yb("securepubads.g.doubleclick.net");yb("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var Gh;try{new URL("s://g"),Gh=!0}catch(a){Gh=!1}var Hh=Gh;function Ih(a){if(a instanceof Hb)a instanceof Hb&&a.constructor===Hb?a=a.h:(Ma(a),a="type_error:SafeUrl");else{b:if(Hh){try{var b=new URL(a)}catch(c){b="https:";break b}b=b.protocol}else c:{b=document.createElement("a");try{b.href=a}catch(c){b=void 0;break c}b=b.protocol;b=":"===b||""===b?"https:":b}a="javascript:"!==b?a:void 0}return a}
;function Jh(a,b){b=Ih(b);void 0!==b&&(a.href=b)}
;var Kh={};function Lh(){}
function Mh(a){this.h=a}
w(Mh,Lh);Mh.prototype.toString=function(){return this.h};function Nh(a){var b="true".toString(),c=[new Mh(Oh[0].toLowerCase(),Kh)];if(0===c.length)throw Error("");if(c.map(function(d){if(d instanceof Mh)d=d.h;else throw Error("");return d}).every(function(d){return 0!=="data-loaded".indexOf(d)}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;function Ph(){throw Error("unknown trace type");}
;var Qh="alternate author bookmark canonical cite help icon license next prefetch dns-prefetch prerender preconnect preload prev search subresource".split(" ");function Rh(a,b){if(b instanceof Cb)a.href=Db(b).toString();else{if(-1===Qh.indexOf("stylesheet"))throw Error('TrustedResourceUrl href attribute required with rel="stylesheet"');b=Ih(b);if(void 0===b)return;a.href=b}a.rel="stylesheet"}
;function Sh(a){var b,c,d=null==(c=(b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:c.call(b,"script[nonce]");(b=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",b)}
function Th(a,b){a.src=Db(b);Sh(a)}
;var Uh=fa([""]),Vh=ia(["\x00"],["\\0"]),Wh=ia(["\n"],["\\n"]),Xh=ia(["\x00"],["\\u0000"]);function Yh(a){return-1===a.toString().indexOf("`")}
Yh(function(a){return a(Uh)})||Yh(function(a){return a(Vh)})||Yh(function(a){return a(Wh)})||Yh(function(a){return a(Xh)});function Zh(a){this.ye=a}
function $h(a){return new Zh(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var ai=[$h("data"),$h("http"),$h("https"),$h("mailto"),$h("ftp"),new Zh(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function bi(a){var b=ci;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function di(){var a=[];bi(function(b){a.push(b)});
return a}
var ci={mf:"allow-forms",nf:"allow-modals",pf:"allow-orientation-lock",qf:"allow-pointer-lock",rf:"allow-popups",sf:"allow-popups-to-escape-sandbox",tf:"allow-presentation",uf:"allow-same-origin",vf:"allow-scripts",wf:"allow-top-navigation",xf:"allow-top-navigation-by-user-activation"},ei=bb(function(){return di()});
function fi(){var a=gi(),b={};db(ei(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function gi(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function hi(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var ii=(new Date).getTime();"undefined"!==typeof TextDecoder&&new TextDecoder;var ji="undefined"!==typeof TextEncoder?new TextEncoder:null,ki=ji?function(a){return ji.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
128>e?b[c++]=e:(2048>e?b[c++]=e>>6|192:(55296==(e&64512)&&d+1<a.length&&56320==(a.charCodeAt(d+1)&64512)?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};function li(a){ud.call(this);var b=this;this.s=this.j=0;this.Ea=null!=a?a:{oa:function(e,f){return setTimeout(e,f)},
qa:function(e){clearTimeout(e)}};
var c,d;this.i=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.l=function(){return A(function(e){return e.yield(mi(b),0)})};
window.addEventListener("offline",this.l);window.addEventListener("online",this.l);this.s||ni(this)}
w(li,ud);function oi(){var a=pi;li.h||(li.h=new li(a));return li.h}
li.prototype.dispose=function(){window.removeEventListener("offline",this.l);window.removeEventListener("online",this.l);this.Ea.qa(this.s);delete li.h};
li.prototype.wa=function(){return this.i};
function ni(a){a.s=a.Ea.oa(function(){var b;return A(function(c){if(1==c.h)return a.i?(null==(b=window.navigator)?0:b.onLine)?c.v(3):c.yield(mi(a),3):c.yield(mi(a),3);ni(a);c.h=0})},3E4)}
function mi(a,b){return a.m?a.m:a.m=new Promise(function(c){var d,e,f,g;return A(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,za(h,2,3),d&&(a.j=a.Ea.oa(function(){d.abort()},b||2E4)),h.yield(fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:h.D=[h.j];h.l=0;h.G=0;a.m=void 0;a.j&&(a.Ea.qa(a.j),a.j=0);g!==a.i&&(a.i=g,a.i?vd(a,"networkstatus-online"):vd(a,"networkstatus-offline"));c(g);Ba(h);break;case 2:Aa(h),g=!1,h.v(3)}})})}
;function qi(){this.data=[];this.h=-1}
qi.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data[a]!==b&&(this.data[a]=b,this.h=-1)};
qi.prototype.get=function(a){return!!this.data[a]};
function ri(a){-1===a.h&&(a.h=a.data.reduce(function(b,c,d){return b+(c?Math.pow(2,d):0)},0));
return a.h}
;function si(a,b){this.h=a[C.Symbol.iterator]();this.i=b}
si.prototype[Symbol.iterator]=function(){return this};
si.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value),done:a.done}};
function ti(a,b){return new si(a,b)}
;function ui(){this.blockSize=-1}
;function vi(){this.blockSize=-1;this.blockSize=64;this.h=[];this.m=[];this.G=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
Xa(vi,ui);vi.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function wi(a,b,c){c||(c=0);var d=a.G;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
vi.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.m,f=this.i;d<b;){if(0==f)for(;d<=c;)wi(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){wi(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){wi(this,e);f=0;break}}this.i=f;this.l+=b}};
vi.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.m[c]=b&255,b/=256;wi(this,this.m);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function xi(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function yi(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function zi(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:xi(a).match(/\S+/g)||[],b=0<=cb(a,b));return b}
function Ai(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):zi(a,"inverted-hdpi")&&yi(a,Array.prototype.filter.call(a.classList?a.classList:xi(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function Bi(){}
Bi.prototype.next=function(){return Ci};
var Ci={done:!0,value:void 0};function Di(a){return{value:a,done:!1}}
Bi.prototype.Ga=function(){return this};function Ei(a){if(a instanceof Fi||a instanceof Gi||a instanceof Hi)return a;if("function"==typeof a.next)return new Fi(function(){return a});
if("function"==typeof a[Symbol.iterator])return new Fi(function(){return a[Symbol.iterator]()});
if("function"==typeof a.Ga)return new Fi(function(){return a.Ga()});
throw Error("Not an iterator or iterable.");}
function Fi(a){this.i=a}
Fi.prototype.Ga=function(){return new Gi(this.i())};
Fi.prototype[Symbol.iterator]=function(){return new Hi(this.i())};
Fi.prototype.h=function(){return new Hi(this.i())};
function Gi(a){this.i=a}
w(Gi,Bi);Gi.prototype.next=function(){return this.i.next()};
Gi.prototype[Symbol.iterator]=function(){return new Hi(this.i)};
Gi.prototype.h=function(){return new Hi(this.i)};
function Hi(a){Fi.call(this,function(){return a});
this.j=a}
w(Hi,Fi);Hi.prototype.next=function(){return this.j.next()};function Ii(a,b){this.i={};this.h=[];this.Ya=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof Ii)for(c=a.Hc(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
m=Ii.prototype;m.Hc=function(){Ji(this);return this.h.concat()};
m.has=function(a){return Ki(this.i,a)};
m.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||Li;Ji(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function Li(a,b){return a===b}
m.isEmpty=function(){return 0==this.size};
m.clear=function(){this.i={};this.Ya=this.size=this.h.length=0};
m.remove=function(a){return this.delete(a)};
m.delete=function(a){return Ki(this.i,a)?(delete this.i[a],--this.size,this.Ya++,this.h.length>2*this.size&&Ji(this),!0):!1};
function Ji(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];Ki(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],Ki(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
m.get=function(a,b){return Ki(this.i,a)?this.i[a]:b};
m.set=function(a,b){Ki(this.i,a)||(this.size+=1,this.h.push(a),this.Ya++);this.i[a]=b};
m.forEach=function(a,b){for(var c=this.Hc(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
m.clone=function(){return new Ii(this)};
m.keys=function(){return Ei(this.Ga(!0)).h()};
m.values=function(){return Ei(this.Ga(!1)).h()};
m.entries=function(){var a=this;return ti(this.keys(),function(b){return[b,a.get(b)]})};
m.Ga=function(a){Ji(this);var b=0,c=this.Ya,d=this,e=new Bi;e.next=function(){if(c!=d.Ya)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)return Ci;var f=d.h[b++];return Di(a?f:d.i[f])};
return e};
function Ki(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function L(a){G.call(this);this.m=1;this.j=[];this.l=0;this.h=[];this.i={};this.s=!!a}
Xa(L,G);m=L.prototype;m.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.m;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.m=e+3;d.push(e);return e};
m.unsubscribe=function(a,b,c){if(a=this.i[a]){var d=this.h;if(a=a.find(function(e){return d[e+1]==b&&d[e+2]==c}))return this.Jb(a)}return!1};
m.Jb=function(a){var b=this.h[a];if(b){var c=this.i[b];0!=this.l?(this.j.push(a),this.h[a+1]=function(){}):(c&&ib(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
m.ab=function(a,b){var c=this.i[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.s)for(e=0;e<c.length;e++){var g=c[e];Mi(this.h[g+1],this.h[g+2],d)}else{this.l++;try{for(e=0,f=c.length;e<f&&!this.Z();e++)g=c[e],this.h[g+1].apply(this.h[g+2],d)}finally{if(this.l--,0<this.j.length&&0==this.l)for(;c=this.j.pop();)this.Jb(c)}}return 0!=e}return!1};
function Mi(a,b,c){Od(function(){a.apply(b,c)})}
m.clear=function(a){if(a){var b=this.i[a];b&&(b.forEach(this.Jb,this),delete this.i[a])}else this.h.length=0,this.i={}};
m.M=function(){L.Aa.M.call(this);this.clear();this.j.length=0};function Ni(a){this.h=a}
Ni.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,(new bh).serialize(b))};
Ni.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Ni.prototype.remove=function(a){this.h.remove(a)};function Oi(a){this.h=a}
Xa(Oi,Ni);function Pi(a){this.data=a}
function Qi(a){return void 0===a||a instanceof Pi?a:new Pi(a)}
Oi.prototype.set=function(a,b){Oi.Aa.set.call(this,a,Qi(b))};
Oi.prototype.i=function(a){a=Oi.Aa.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Oi.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Ri(a){this.h=a}
Xa(Ri,Oi);Ri.prototype.set=function(a,b,c){if(b=Qi(b)){if(c){if(c<Wa()){Ri.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Wa()}Ri.Aa.set.call(this,a,b)};
Ri.prototype.i=function(a){var b=Ri.Aa.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Wa()||c&&c>Wa())Ri.prototype.remove.call(this,a);else return b}};function Si(){}
;function Ti(){}
Xa(Ti,Si);Ti.prototype[Symbol.iterator]=function(){return Ei(this.Ga(!0)).h()};
Ti.prototype.clear=function(){var a=Array.from(this);a=v(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function Ui(a){this.h=a}
Xa(Ui,Ti);m=Ui.prototype;m.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
m.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
m.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeItem(a)};
m.Ga=function(a){var b=0,c=this.h,d=new Bi;d.next=function(){if(b>=c.length)return Ci;var e=c.key(b++);if(a)return Di(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Di(e)};
return d};
m.clear=function(){this.h.clear()};
m.key=function(a){return this.h.key(a)};function Vi(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
Xa(Vi,Ui);function Wi(a,b){this.i=a;this.h=null;var c;if(c=Jc)c=!(9<=Number(Xc));if(c){Xi||(Xi=new Ii);this.h=Xi.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),Xi.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
Xa(Wi,Ti);var Yi={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},Xi=null;function Zi(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return Yi[b]})}
m=Wi.prototype;m.isAvailable=function(){return!!this.h};
m.set=function(a,b){this.h.setAttribute(Zi(a),b);$i(this)};
m.get=function(a){a=this.h.getAttribute(Zi(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeAttribute(Zi(a));$i(this)};
m.Ga=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new Bi;d.next=function(){if(b>=c.length)return Ci;var e=c[b++];if(a)return Di(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Di(e)};
return d};
m.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);$i(this)};
function $i(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function aj(a,b){this.i=a;this.h=b+"::"}
Xa(aj,Ti);aj.prototype.set=function(a,b){this.i.set(this.h+a,b)};
aj.prototype.get=function(a){return this.i.get(this.h+a)};
aj.prototype.remove=function(a){this.i.remove(this.h+a)};
aj.prototype.Ga=function(a){var b=this.i[Symbol.iterator](),c=this,d=new Bi;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return Di(a?e.slice(c.h.length):c.i.get(e))};
return d};/*

 (The MIT License)

 Copyright (C) 2014 by Vitaly Puzrin

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.

 -----------------------------------------------------------------------------
 Ported from zlib, which is under the following license
 https://github.com/madler/zlib/blob/master/zlib.h

 zlib.h -- interface of the 'zlib' general purpose compression library
   version 1.2.8, April 28th, 2013
   Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
   This software is provided 'as-is', without any express or implied
   warranty.  In no event will the authors be held liable for any damages
   arising from the use of this software.
   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:
   1. The origin of this software must not be misrepresented; you must not
      claim that you wrote the original software. If you use this software
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
   Jean-loup Gailly        Mark Adler
   jloup@gzip.org          madler@alumni.caltech.edu
   The data format used by the zlib library is described by RFCs (Request for
   Comments) 1950 to 1952 in the files http://tools.ietf.org/html/rfc1950
   (zlib format), rfc1951 (deflate format) and rfc1952 (gzip format).
*/
var O={},bj="undefined"!==typeof Uint8Array&&"undefined"!==typeof Uint16Array&&"undefined"!==typeof Int32Array;O.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if("object"!==typeof c)throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
O.Vc=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var cj={rb:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
nd:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},dj={rb:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
nd:function(a){return[].concat.apply([],a)}};
O.Ye=function(){bj?(O.ob=Uint8Array,O.Ia=Uint16Array,O.Rd=Int32Array,O.assign(O,cj)):(O.ob=Array,O.Ia=Array,O.Rd=Array,O.assign(O,dj))};
O.Ye();var ej=!0;try{new Uint8Array(1)}catch(a){ej=!1}
function fj(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if(55296===(f&64512)&&b+1<d){var g=a.charCodeAt(b+1);56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=128>f?1:2048>f?2:65536>f?3:4}var h=new O.ob(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),55296===(f&64512)&&b+1<d&&(g=a.charCodeAt(b+1),56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)),128>f?h[c++]=f:(2048>f?h[c++]=192|f>>>6:(65536>f?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var gj={};gj=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;0!==c;){f=2E3<c?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var hj={},ij,jj=[],kj=0;256>kj;kj++){ij=kj;for(var lj=0;8>lj;lj++)ij=ij&1?3988292384^ij>>>1:ij>>>1;jj[kj]=ij}hj=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^jj[(a^b[d])&255];return a^-1};var mj={};mj={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function nj(a){for(var b=a.length;0<=--b;)a[b]=0}
var oj=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],pj=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],qj=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],rj=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],sj=Array(576);nj(sj);var tj=Array(60);nj(tj);var uj=Array(512);nj(uj);var vj=Array(256);nj(vj);var wj=Array(29);nj(wj);var xj=Array(30);nj(xj);function yj(a,b,c,d,e){this.Jd=a;this.je=b;this.he=c;this.ce=d;this.Ce=e;this.rd=a&&a.length}
var zj,Aj,Bj;function Cj(a,b){this.md=a;this.Eb=0;this.Xa=b}
function Dj(a,b){a.V[a.pending++]=b&255;a.V[a.pending++]=b>>>8&255}
function Ej(a,b,c){a.fa>16-c?(a.ka|=b<<a.fa&65535,Dj(a,a.ka),a.ka=b>>16-a.fa,a.fa+=c-16):(a.ka|=b<<a.fa&65535,a.fa+=c)}
function Fj(a,b,c){Ej(a,c[2*b],c[2*b+1])}
function Gj(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(0<--b);return c>>>1}
function Hj(a,b,c){var d=Array(16),e=0,f;for(f=1;15>=f;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[2*c+1],0!==e&&(a[2*c]=Gj(d[e]++,e))}
function Ij(a){var b;for(b=0;286>b;b++)a.ra[2*b]=0;for(b=0;30>b;b++)a.eb[2*b]=0;for(b=0;19>b;b++)a.ga[2*b]=0;a.ra[512]=1;a.Pa=a.Ib=0;a.ya=a.matches=0}
function Jj(a){8<a.fa?Dj(a,a.ka):0<a.fa&&(a.V[a.pending++]=a.ka);a.ka=0;a.fa=0}
function Kj(a,b,c){Jj(a);Dj(a,c);Dj(a,~c);O.rb(a.V,a.window,b,c,a.pending);a.pending+=c}
function Lj(a,b,c,d){var e=2*b,f=2*c;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function Mj(a,b,c){for(var d=a.X[c],e=c<<1;e<=a.Na;){e<a.Na&&Lj(b,a.X[e+1],a.X[e],a.depth)&&e++;if(Lj(b,d,a.X[e],a.depth))break;a.X[c]=a.X[e];c=e;e<<=1}a.X[c]=d}
function Nj(a,b,c){var d=0;if(0!==a.ya){do{var e=a.V[a.Nb+2*d]<<8|a.V[a.Nb+2*d+1];var f=a.V[a.Lc+d];d++;if(0===e)Fj(a,f,b);else{var g=vj[f];Fj(a,g+256+1,b);var h=oj[g];0!==h&&(f-=wj[g],Ej(a,f,h));e--;g=256>e?uj[e]:uj[256+(e>>>7)];Fj(a,g,c);h=pj[g];0!==h&&(e-=xj[g],Ej(a,e,h))}}while(d<a.ya)}Fj(a,256,b)}
function Oj(a,b){var c=b.md,d=b.Xa.Jd,e=b.Xa.rd,f=b.Xa.ce,g,h=-1;a.Na=0;a.yb=573;for(g=0;g<f;g++)0!==c[2*g]?(a.X[++a.Na]=h=g,a.depth[g]=0):c[2*g+1]=0;for(;2>a.Na;){var k=a.X[++a.Na]=2>h?++h:0;c[2*k]=1;a.depth[k]=0;a.Pa--;e&&(a.Ib-=d[2*k+1])}b.Eb=h;for(g=a.Na>>1;1<=g;g--)Mj(a,c,g);k=f;do g=a.X[1],a.X[1]=a.X[a.Na--],Mj(a,c,1),d=a.X[1],a.X[--a.yb]=g,a.X[--a.yb]=d,c[2*k]=c[2*g]+c[2*d],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[2*g+1]=c[2*d+1]=k,a.X[1]=k++,Mj(a,c,1);while(2<=a.Na);a.X[--a.yb]=
a.X[1];g=b.md;k=b.Eb;d=b.Xa.Jd;e=b.Xa.rd;f=b.Xa.je;var l=b.Xa.he,n=b.Xa.Ce,r,t=0;for(r=0;15>=r;r++)a.Ka[r]=0;g[2*a.X[a.yb]+1]=0;for(b=a.yb+1;573>b;b++){var p=a.X[b];r=g[2*g[2*p+1]+1]+1;r>n&&(r=n,t++);g[2*p+1]=r;if(!(p>k)){a.Ka[r]++;var x=0;p>=l&&(x=f[p-l]);var y=g[2*p];a.Pa+=y*(r+x);e&&(a.Ib+=y*(d[2*p+1]+x))}}if(0!==t){do{for(r=n-1;0===a.Ka[r];)r--;a.Ka[r]--;a.Ka[r+1]+=2;a.Ka[n]--;t-=2}while(0<t);for(r=n;0!==r;r--)for(p=a.Ka[r];0!==p;)d=a.X[--b],d>k||(g[2*d+1]!==r&&(a.Pa+=(r-g[2*d+1])*g[2*d],g[2*
d+1]=r),p--)}Hj(c,h,a.Ka)}
function Pj(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);b[2*(c+1)+1]=65535;for(d=0;d<=c;d++){var l=f;f=b[2*(d+1)+1];++g<h&&l===f||(g<k?a.ga[2*l]+=g:0!==l?(l!==e&&a.ga[2*l]++,a.ga[32]++):10>=g?a.ga[34]++:a.ga[36]++,g=0,e=l,0===f?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4))}}
function Qj(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);for(d=0;d<=c;d++){var l=f;f=b[2*(d+1)+1];if(!(++g<h&&l===f)){if(g<k){do Fj(a,l,a.ga);while(0!==--g)}else 0!==l?(l!==e&&(Fj(a,l,a.ga),g--),Fj(a,16,a.ga),Ej(a,g-3,2)):10>=g?(Fj(a,17,a.ga),Ej(a,g-3,3)):(Fj(a,18,a.ga),Ej(a,g-11,7));g=0;e=l;0===f?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4)}}}
function Rj(a){var b=4093624447,c;for(c=0;31>=c;c++,b>>>=1)if(b&1&&0!==a.ra[2*c])return 0;if(0!==a.ra[18]||0!==a.ra[20]||0!==a.ra[26])return 1;for(c=32;256>c;c++)if(0!==a.ra[2*c])return 1;return 0}
var Sj=!1;function Tj(a,b,c){a.V[a.Nb+2*a.ya]=b>>>8&255;a.V[a.Nb+2*a.ya+1]=b&255;a.V[a.Lc+a.ya]=c&255;a.ya++;0===b?a.ra[2*c]++:(a.matches++,b--,a.ra[2*(vj[c]+256+1)]++,a.eb[2*(256>b?uj[b]:uj[256+(b>>>7)])]++);return a.ya===a.Qb-1}
;function Uj(a,b){a.msg=mj[b];return b}
function Vj(a){for(var b=a.length;0<=--b;)a[b]=0}
function Wj(a){var b=a.state,c=b.pending;c>a.K&&(c=a.K);0!==c&&(O.rb(a.output,b.V,b.Tb,c,a.Fb),a.Fb+=c,b.Tb+=c,a.Wc+=c,a.K-=c,b.pending-=c,0===b.pending&&(b.Tb=0))}
function Xj(a,b){var c=0<=a.ta?a.ta:-1,d=a.o-a.ta,e=0;if(0<a.level){2===a.H.Bc&&(a.H.Bc=Rj(a));Oj(a,a.hc);Oj(a,a.cc);Pj(a,a.ra,a.hc.Eb);Pj(a,a.eb,a.cc.Eb);Oj(a,a.ed);for(e=18;3<=e&&0===a.ga[2*rj[e]+1];e--);a.Pa+=3*(e+1)+14;var f=a.Pa+3+7>>>3;var g=a.Ib+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&-1!==c)Ej(a,b?1:0,3),Kj(a,c,d);else if(4===a.strategy||g===f)Ej(a,2+(b?1:0),3),Nj(a,sj,tj);else{Ej(a,4+(b?1:0),3);c=a.hc.Eb+1;d=a.cc.Eb+1;e+=1;Ej(a,c-257,5);Ej(a,d-1,5);Ej(a,e-4,4);for(f=0;f<e;f++)Ej(a,a.ga[2*
rj[f]+1],3);Qj(a,a.ra,c-1);Qj(a,a.eb,d-1);Nj(a,a.ra,a.eb)}Ij(a);b&&Jj(a);a.ta=a.o;Wj(a.H)}
function P(a,b){a.V[a.pending++]=b}
function Yj(a,b){a.V[a.pending++]=b>>>8&255;a.V[a.pending++]=b&255}
function Zj(a,b){var c=a.ud,d=a.o,e=a.xa,f=a.wd,g=a.o>a.ia-262?a.o-(a.ia-262):0,h=a.window,k=a.Za,l=a.Ha,n=a.o+258,r=h[d+e-1],t=h[d+e];a.xa>=a.qd&&(c>>=2);f>a.u&&(f=a.u);do{var p=b;if(h[p+e]===t&&h[p+e-1]===r&&h[p]===h[d]&&h[++p]===h[d+1]){d+=2;for(p++;h[++d]===h[++p]&&h[++d]===h[++p]&&h[++d]===h[++p]&&h[++d]===h[++p]&&h[++d]===h[++p]&&h[++d]===h[++p]&&h[++d]===h[++p]&&h[++d]===h[++p]&&d<n;);p=258-(n-d);d=n-258;if(p>e){a.Db=b;e=p;if(p>=f)break;r=h[d+e-1];t=h[d+e]}}}while((b=l[b&k])>g&&0!==--c);return e<=
a.u?e:a.u}
function ak(a){var b=a.ia,c;do{var d=a.Pd-a.u-a.o;if(a.o>=b+(b-262)){O.rb(a.window,a.window,b,b,0);a.Db-=b;a.o-=b;a.ta-=b;var e=c=a.fc;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Ha[--e],a.Ha[e]=f>=b?f-b:0;while(--c);d+=b}if(0===a.H.ja)break;e=a.H;c=a.window;f=a.o+a.u;var g=e.ja;g>d&&(g=d);0===g?c=0:(e.ja-=g,O.rb(c,e.input,e.jb,g,f),1===e.state.wrap?e.F=gj(e.F,c,g,f):2===e.state.wrap&&(e.F=hj(e.F,c,g,f)),e.jb+=g,e.nb+=g,c=g);a.u+=c;if(3<=a.u+a.sa)for(d=a.o-a.sa,a.J=a.window[d],
a.J=(a.J<<a.Ma^a.window[d+1])&a.La;a.sa&&!(a.J=(a.J<<a.Ma^a.window[d+3-1])&a.La,a.Ha[d&a.Za]=a.head[a.J],a.head[a.J]=d,d++,a.sa--,3>a.u+a.sa););}while(262>a.u&&0!==a.H.ja)}
function bk(a,b){for(var c;;){if(262>a.u){ak(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.J=(a.J<<a.Ma^a.window[a.o+3-1])&a.La,c=a.Ha[a.o&a.Za]=a.head[a.J],a.head[a.J]=a.o);0!==c&&a.o-c<=a.ia-262&&(a.P=Zj(a,c));if(3<=a.P)if(c=Tj(a,a.o-a.Db,a.P-3),a.u-=a.P,a.P<=a.Mc&&3<=a.u){a.P--;do a.o++,a.J=(a.J<<a.Ma^a.window[a.o+3-1])&a.La,a.Ha[a.o&a.Za]=a.head[a.J],a.head[a.J]=a.o;while(0!==--a.P);a.o++}else a.o+=a.P,a.P=0,a.J=a.window[a.o],a.J=(a.J<<a.Ma^a.window[a.o+1])&a.La;else c=Tj(a,0,
a.window[a.o]),a.u--,a.o++;if(c&&(Xj(a,!1),0===a.H.K))return 1}a.sa=2>a.o?a.o:2;return 4===b?(Xj(a,!0),0===a.H.K?3:4):a.ya&&(Xj(a,!1),0===a.H.K)?1:2}
function ck(a,b){for(var c,d;;){if(262>a.u){ak(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.J=(a.J<<a.Ma^a.window[a.o+3-1])&a.La,c=a.Ha[a.o&a.Za]=a.head[a.J],a.head[a.J]=a.o);a.xa=a.P;a.zd=a.Db;a.P=2;0!==c&&a.xa<a.Mc&&a.o-c<=a.ia-262&&(a.P=Zj(a,c),5>=a.P&&(1===a.strategy||3===a.P&&4096<a.o-a.Db)&&(a.P=2));if(3<=a.xa&&a.P<=a.xa){d=a.o+a.u-3;c=Tj(a,a.o-1-a.zd,a.xa-3);a.u-=a.xa-1;a.xa-=2;do++a.o<=d&&(a.J=(a.J<<a.Ma^a.window[a.o+3-1])&a.La,a.Ha[a.o&a.Za]=a.head[a.J],a.head[a.J]=a.o);
while(0!==--a.xa);a.hb=0;a.P=2;a.o++;if(c&&(Xj(a,!1),0===a.H.K))return 1}else if(a.hb){if((c=Tj(a,0,a.window[a.o-1]))&&Xj(a,!1),a.o++,a.u--,0===a.H.K)return 1}else a.hb=1,a.o++,a.u--}a.hb&&(Tj(a,0,a.window[a.o-1]),a.hb=0);a.sa=2>a.o?a.o:2;return 4===b?(Xj(a,!0),0===a.H.K?3:4):a.ya&&(Xj(a,!1),0===a.H.K)?1:2}
function dk(a,b){for(var c,d,e,f=a.window;;){if(258>=a.u){ak(a);if(258>=a.u&&0===b)return 1;if(0===a.u)break}a.P=0;if(3<=a.u&&0<a.o&&(d=a.o-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.o+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.P=258-(e-d);a.P>a.u&&(a.P=a.u)}3<=a.P?(c=Tj(a,1,a.P-3),a.u-=a.P,a.o+=a.P,a.P=0):(c=Tj(a,0,a.window[a.o]),a.u--,a.o++);if(c&&(Xj(a,!1),0===a.H.K))return 1}a.sa=0;return 4===b?(Xj(a,!0),0===a.H.K?3:4):
a.ya&&(Xj(a,!1),0===a.H.K)?1:2}
function ek(a,b){for(var c;;){if(0===a.u&&(ak(a),0===a.u)){if(0===b)return 1;break}a.P=0;c=Tj(a,0,a.window[a.o]);a.u--;a.o++;if(c&&(Xj(a,!1),0===a.H.K))return 1}a.sa=0;return 4===b?(Xj(a,!0),0===a.H.K?3:4):a.ya&&(Xj(a,!1),0===a.H.K)?1:2}
function fk(a,b,c,d,e){this.pe=a;this.Be=b;this.Ee=c;this.Ae=d;this.le=e}
var gk;gk=[new fk(0,0,0,0,function(a,b){var c=65535;for(c>a.za-5&&(c=a.za-5);;){if(1>=a.u){ak(a);if(0===a.u&&0===b)return 1;if(0===a.u)break}a.o+=a.u;a.u=0;var d=a.ta+c;if(0===a.o||a.o>=d)if(a.u=a.o-d,a.o=d,Xj(a,!1),0===a.H.K)return 1;if(a.o-a.ta>=a.ia-262&&(Xj(a,!1),0===a.H.K))return 1}a.sa=0;if(4===b)return Xj(a,!0),0===a.H.K?3:4;a.o>a.ta&&Xj(a,!1);return 1}),
new fk(4,4,8,4,bk),new fk(4,5,16,8,bk),new fk(4,6,32,32,bk),new fk(4,4,16,16,ck),new fk(8,16,32,32,ck),new fk(8,16,128,128,ck),new fk(8,32,128,256,ck),new fk(32,128,258,1024,ck),new fk(32,258,258,4096,ck)];
function hk(){this.H=null;this.status=0;this.V=null;this.wrap=this.pending=this.Tb=this.za=0;this.B=null;this.Ca=0;this.method=8;this.Bb=-1;this.Za=this.Yc=this.ia=0;this.window=null;this.Pd=0;this.head=this.Ha=null;this.wd=this.qd=this.strategy=this.level=this.Mc=this.ud=this.xa=this.u=this.Db=this.o=this.hb=this.zd=this.P=this.ta=this.Ma=this.La=this.Ic=this.fc=this.J=0;this.ra=new O.Ia(1146);this.eb=new O.Ia(122);this.ga=new O.Ia(78);Vj(this.ra);Vj(this.eb);Vj(this.ga);this.ed=this.cc=this.hc=
null;this.Ka=new O.Ia(16);this.X=new O.Ia(573);Vj(this.X);this.yb=this.Na=0;this.depth=new O.Ia(573);Vj(this.depth);this.fa=this.ka=this.sa=this.matches=this.Ib=this.Pa=this.Nb=this.ya=this.Qb=this.Lc=0}
function ik(a,b){if(!a||!a.state||5<b||0>b)return a?Uj(a,-2):-2;var c=a.state;if(!a.output||!a.input&&0!==a.ja||666===c.status&&4!==b)return Uj(a,0===a.K?-5:-2);c.H=a;var d=c.Bb;c.Bb=b;if(42===c.status)if(2===c.wrap)a.F=0,P(c,31),P(c,139),P(c,8),c.B?(P(c,(c.B.text?1:0)+(c.B.Ua?2:0)+(c.B.Ta?4:0)+(c.B.name?8:0)+(c.B.comment?16:0)),P(c,c.B.time&255),P(c,c.B.time>>8&255),P(c,c.B.time>>16&255),P(c,c.B.time>>24&255),P(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),P(c,c.B.os&255),c.B.Ta&&c.B.Ta.length&&
(P(c,c.B.Ta.length&255),P(c,c.B.Ta.length>>8&255)),c.B.Ua&&(a.F=hj(a.F,c.V,c.pending,0)),c.Ca=0,c.status=69):(P(c,0),P(c,0),P(c,0),P(c,0),P(c,0),P(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),P(c,3),c.status=113);else{var e=8+(c.Yc-8<<4)<<8;e|=(2<=c.strategy||2>c.level?0:6>c.level?1:6===c.level?2:3)<<6;0!==c.o&&(e|=32);c.status=113;Yj(c,e+(31-e%31));0!==c.o&&(Yj(c,a.F>>>16),Yj(c,a.F&65535));a.F=1}if(69===c.status)if(c.B.Ta){for(e=c.pending;c.Ca<(c.B.Ta.length&65535)&&(c.pending!==c.za||(c.B.Ua&&
c.pending>e&&(a.F=hj(a.F,c.V,c.pending-e,e)),Wj(a),e=c.pending,c.pending!==c.za));)P(c,c.B.Ta[c.Ca]&255),c.Ca++;c.B.Ua&&c.pending>e&&(a.F=hj(a.F,c.V,c.pending-e,e));c.Ca===c.B.Ta.length&&(c.Ca=0,c.status=73)}else c.status=73;if(73===c.status)if(c.B.name){e=c.pending;do{if(c.pending===c.za&&(c.B.Ua&&c.pending>e&&(a.F=hj(a.F,c.V,c.pending-e,e)),Wj(a),e=c.pending,c.pending===c.za)){var f=1;break}f=c.Ca<c.B.name.length?c.B.name.charCodeAt(c.Ca++)&255:0;P(c,f)}while(0!==f);c.B.Ua&&c.pending>e&&(a.F=hj(a.F,
c.V,c.pending-e,e));0===f&&(c.Ca=0,c.status=91)}else c.status=91;if(91===c.status)if(c.B.comment){e=c.pending;do{if(c.pending===c.za&&(c.B.Ua&&c.pending>e&&(a.F=hj(a.F,c.V,c.pending-e,e)),Wj(a),e=c.pending,c.pending===c.za)){f=1;break}f=c.Ca<c.B.comment.length?c.B.comment.charCodeAt(c.Ca++)&255:0;P(c,f)}while(0!==f);c.B.Ua&&c.pending>e&&(a.F=hj(a.F,c.V,c.pending-e,e));0===f&&(c.status=103)}else c.status=103;103===c.status&&(c.B.Ua?(c.pending+2>c.za&&Wj(a),c.pending+2<=c.za&&(P(c,a.F&255),P(c,a.F>>
8&255),a.F=0,c.status=113)):c.status=113);if(0!==c.pending){if(Wj(a),0===a.K)return c.Bb=-1,0}else if(0===a.ja&&(b<<1)-(4<b?9:0)<=(d<<1)-(4<d?9:0)&&4!==b)return Uj(a,-5);if(666===c.status&&0!==a.ja)return Uj(a,-5);if(0!==a.ja||0!==c.u||0!==b&&666!==c.status){d=2===c.strategy?ek(c,b):3===c.strategy?dk(c,b):gk[c.level].le(c,b);if(3===d||4===d)c.status=666;if(1===d||3===d)return 0===a.K&&(c.Bb=-1),0;if(2===d&&(1===b?(Ej(c,2,3),Fj(c,256,sj),16===c.fa?(Dj(c,c.ka),c.ka=0,c.fa=0):8<=c.fa&&(c.V[c.pending++]=
c.ka&255,c.ka>>=8,c.fa-=8)):5!==b&&(Ej(c,0,3),Kj(c,0,0),3===b&&(Vj(c.head),0===c.u&&(c.o=0,c.ta=0,c.sa=0))),Wj(a),0===a.K))return c.Bb=-1,0}if(4!==b)return 0;if(0>=c.wrap)return 1;2===c.wrap?(P(c,a.F&255),P(c,a.F>>8&255),P(c,a.F>>16&255),P(c,a.F>>24&255),P(c,a.nb&255),P(c,a.nb>>8&255),P(c,a.nb>>16&255),P(c,a.nb>>24&255)):(Yj(c,a.F>>>16),Yj(c,a.F&65535));Wj(a);0<c.wrap&&(c.wrap=-c.wrap);return 0!==c.pending?0:1}
;var jk={};jk=function(){this.input=null;this.nb=this.ja=this.jb=0;this.output=null;this.Wc=this.K=this.Fb=0;this.msg="";this.state=null;this.Bc=2;this.F=0};var kk=Object.prototype.toString;
function lk(a){if(!(this instanceof lk))return new lk(a);a=this.options=O.assign({level:-1,method:8,chunkSize:16384,windowBits:15,memLevel:8,strategy:0,to:""},a||{});a.raw&&0<a.windowBits?a.windowBits=-a.windowBits:a.gzip&&0<a.windowBits&&16>a.windowBits&&(a.windowBits+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.H=new jk;this.H.K=0;var b=this.H;var c=a.level,d=a.method,e=a.windowBits,f=a.memLevel,g=a.strategy;if(b){var h=1;-1===c&&(c=6);0>e?(h=0,e=-e):15<e&&(h=2,e-=16);if(1>f||9<
f||8!==d||8>e||15<e||0>c||9<c||0>g||4<g)b=Uj(b,-2);else{8===e&&(e=9);var k=new hk;b.state=k;k.H=b;k.wrap=h;k.B=null;k.Yc=e;k.ia=1<<k.Yc;k.Za=k.ia-1;k.Ic=f+7;k.fc=1<<k.Ic;k.La=k.fc-1;k.Ma=~~((k.Ic+3-1)/3);k.window=new O.ob(2*k.ia);k.head=new O.Ia(k.fc);k.Ha=new O.Ia(k.ia);k.Qb=1<<f+6;k.za=4*k.Qb;k.V=new O.ob(k.za);k.Nb=1*k.Qb;k.Lc=3*k.Qb;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.nb=b.Wc=0;b.Bc=2;c=b.state;c.pending=0;c.Tb=0;0>c.wrap&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.F=2===c.wrap?
0:1;c.Bb=0;if(!Sj){d=Array(16);for(f=g=0;28>f;f++)for(wj[f]=g,e=0;e<1<<oj[f];e++)vj[g++]=f;vj[g-1]=f;for(f=g=0;16>f;f++)for(xj[f]=g,e=0;e<1<<pj[f];e++)uj[g++]=f;for(g>>=7;30>f;f++)for(xj[f]=g<<7,e=0;e<1<<pj[f]-7;e++)uj[256+g++]=f;for(e=0;15>=e;e++)d[e]=0;for(e=0;143>=e;)sj[2*e+1]=8,e++,d[8]++;for(;255>=e;)sj[2*e+1]=9,e++,d[9]++;for(;279>=e;)sj[2*e+1]=7,e++,d[7]++;for(;287>=e;)sj[2*e+1]=8,e++,d[8]++;Hj(sj,287,d);for(e=0;30>e;e++)tj[2*e+1]=5,tj[2*e]=Gj(e,5);zj=new yj(sj,oj,257,286,15);Aj=new yj(tj,
pj,0,30,15);Bj=new yj([],qj,0,19,7);Sj=!0}c.hc=new Cj(c.ra,zj);c.cc=new Cj(c.eb,Aj);c.ed=new Cj(c.ga,Bj);c.ka=0;c.fa=0;Ij(c);c=0}else c=Uj(b,-2);0===c&&(b=b.state,b.Pd=2*b.ia,Vj(b.head),b.Mc=gk[b.level].Be,b.qd=gk[b.level].pe,b.wd=gk[b.level].Ee,b.ud=gk[b.level].Ae,b.o=0,b.ta=0,b.u=0,b.sa=0,b.P=b.xa=2,b.hb=0,b.J=0);b=c}}else b=-2;if(0!==b)throw Error(mj[b]);a.header&&(b=this.H)&&b.state&&2===b.state.wrap&&(b.state.B=a.header);if(a.dictionary){var l;"string"===typeof a.dictionary?l=fj(a.dictionary):
"[object ArrayBuffer]"===kk.call(a.dictionary)?l=new Uint8Array(a.dictionary):l=a.dictionary;a=this.H;f=l;g=f.length;if(a&&a.state)if(l=a.state,b=l.wrap,2===b||1===b&&42!==l.status||l.u)b=-2;else{1===b&&(a.F=gj(a.F,f,g,0));l.wrap=0;g>=l.ia&&(0===b&&(Vj(l.head),l.o=0,l.ta=0,l.sa=0),c=new O.ob(l.ia),O.rb(c,f,g-l.ia,l.ia,0),f=c,g=l.ia);c=a.ja;d=a.jb;e=a.input;a.ja=g;a.jb=0;a.input=f;for(ak(l);3<=l.u;){f=l.o;g=l.u-2;do l.J=(l.J<<l.Ma^l.window[f+3-1])&l.La,l.Ha[f&l.Za]=l.head[l.J],l.head[l.J]=f,f++;while(--g);
l.o=f;l.u=2;ak(l)}l.o+=l.u;l.ta=l.o;l.sa=l.u;l.u=0;l.P=l.xa=2;l.hb=0;a.jb=d;a.input=e;a.ja=c;l.wrap=b;b=0}else b=-2;if(0!==b)throw Error(mj[b]);this.Nf=!0}}
lk.prototype.push=function(a,b){var c=this.H,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:!0===b?4:0;"string"===typeof a?c.input=fj(a):"[object ArrayBuffer]"===kk.call(a)?c.input=new Uint8Array(a):c.input=a;c.jb=0;c.ja=c.input.length;do{0===c.K&&(c.output=new O.ob(d),c.Fb=0,c.K=d);a=ik(c,e);if(1!==a&&0!==a)return mk(this,a),this.ended=!0,!1;if(0===c.K||0===c.ja&&(4===e||2===e))if("string"===this.options.to){var f=O.Vc(c.output,c.Fb);b=f;f=f.length;if(65537>f&&(b.subarray&&ej||!b.subarray))b=
String.fromCharCode.apply(null,O.Vc(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=O.Vc(c.output,c.Fb),this.chunks.push(b)}while((0<c.ja||0===c.K)&&1!==a);if(4===e)return(c=this.H)&&c.state?(d=c.state.status,42!==d&&69!==d&&73!==d&&91!==d&&103!==d&&113!==d&&666!==d?a=Uj(c,-2):(c.state=null,a=113===d?Uj(c,-3):0)):a=-2,mk(this,a),this.ended=!0,0===a;2===e&&(mk(this,0),c.K=0);return!0};
function mk(a,b){0===b&&(a.result="string"===a.options.to?a.chunks.join(""):O.nd(a.chunks));a.chunks=[];a.err=b;a.msg=a.H.msg}
function nk(a,b){b=b||{};b.gzip=!0;b=new lk(b);b.push(a,!0);if(b.err)throw b.msg||mj[b.err];return b.result}
;function ok(a){return Fb(null===a?"null":void 0===a?"undefined":a)}
;function pk(a){this.name=a}
;var qk=new pk("rawColdConfigGroup");var rk=new pk("rawHotConfigGroup");var sk=new pk("commandExecutorCommand");function tk(a){this.A=Cf(a)}
w(tk,cg);var uk=new pk("continuationCommand");var vk=new pk("signalAction");var wk=new pk("webCommandMetadata");var xk=new pk("signalServiceEndpoint");var yk={Cf:"EMBEDDED_PLAYER_MODE_UNKNOWN",zf:"EMBEDDED_PLAYER_MODE_DEFAULT",Bf:"EMBEDDED_PLAYER_MODE_PFP",Af:"EMBEDDED_PLAYER_MODE_PFL"};var zk=new pk("feedbackEndpoint");function Ak(a){this.A=Cf(a)}
w(Ak,cg);var Bk=new pk("webPlayerShareEntityServiceEndpoint");var Ck=new pk("playlistEditEndpoint");var Dk=new pk("modifyChannelNotificationPreferenceEndpoint");var Ek=new pk("unsubscribeEndpoint");var Fk=new pk("subscribeEndpoint");function Gk(){var a=Hk;E("yt.ads.biscotti.getId_")||D("yt.ads.biscotti.getId_",a)}
function Ik(a){D("yt.ads.biscotti.lastId_",a)}
;function Jk(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var Kk=C.window,Lk,Mk,Nk=(null==Kk?void 0:null==(Lk=Kk.yt)?void 0:Lk.config_)||(null==Kk?void 0:null==(Mk=Kk.ytcfg)?void 0:Mk.data_)||{};D("yt.config_",Nk);function Ok(){Jk(Nk,arguments)}
function R(a,b){return a in Nk?Nk[a]:b}
function Pk(a){var b=Nk.EXPERIMENT_FLAGS;return b?b[a]:void 0}
;var Qk=[];function Rk(a){Qk.forEach(function(b){return b(a)})}
function Sk(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Tk(b)}}:a}
function Tk(a){var b=E("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=R("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),Ok("ERRORS",b));Rk(a)}
function Uk(a,b,c,d,e){var f=E("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=R("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),Ok("ERRORS",f))}
;var Vk=/^[\w.]*$/,Wk={q:!0,search_query:!0};function Xk(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Yk(f[0]||""),h=Yk(f[1]||"");g in c?Array.isArray(c[g])?jb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(r){var k=r,l=f[0],n=String(Xk);k.args=[{key:l,value:f[1],query:a,method:Zk==n?"unchanged":n}];Wk.hasOwnProperty(l)||Uk(k)}}return c}
var Zk=String(Xk);function $k(a){var b=[];kb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];db(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function al(a){"?"==a.charAt(0)&&(a=a.substr(1));return Xk(a,"&")}
function bl(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),al(1<a.length?a[1]:a[0])):{}}
function cl(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=al(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return lc(a,e)+d}
function dl(a){if(!b)var b=window.location.href;var c=bc(1,a),d=cc(a);c&&d?(a=a.match($b),b=b.match($b),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?cc(b)==d&&(Number(bc(4,b))||null)==(Number(bc(4,a))||null):!0;return a}
function Yk(a){return a&&a.match(Vk)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function el(a){var b=fl;a=void 0===a?E("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=ii;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Ia){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?Fh:g;try{var h=g.history.length}catch(Ia){h=0}e.u_his=h;var k;e.u_h=null==(k=Fh.screen)?void 0:k.height;var l;e.u_w=null==(l=Fh.screen)?void 0:l.width;var n;e.u_ah=null==(n=Fh.screen)?void 0:n.availHeight;var r;e.u_aw=
null==(r=Fh.screen)?void 0:r.availWidth;var t;e.u_cd=null==(t=Fh.screen)?void 0:t.colorDepth}catch(Ia){}h=b.h;try{var p=h.screenX;var x=h.screenY}catch(Ia){}try{var y=h.outerWidth;var z=h.outerHeight}catch(Ia){}try{var H=h.innerWidth;var I=h.innerHeight}catch(Ia){}try{var M=h.screenLeft;var N=h.screenTop}catch(Ia){}try{H=h.innerWidth,I=h.innerHeight}catch(Ia){}try{var K=h.screen.availWidth;var V=h.screen.availTop}catch(Ia){}p=[M,N,p,x,K,V,y,z,H,I];try{var Z=(b.h.top||window).document,ha="CSS1Compat"==
Z.compatMode?Z.documentElement:Z.body;var qa=(new Bd(ha.clientWidth,ha.clientHeight)).round()}catch(Ia){qa=new Bd(-12245933,-12245933)}Z=qa;qa={};var na=void 0===na?C:na;ha=new qi;"SVGElement"in na&&"createElementNS"in na.document&&ha.set(0);x=fi();x["allow-top-navigation-by-user-activation"]&&ha.set(1);x["allow-popups-to-escape-sandbox"]&&ha.set(2);na.crypto&&na.crypto.subtle&&ha.set(3);"TextDecoder"in na&&"TextEncoder"in na&&ha.set(4);na=ri(ha);qa.bc=na;qa.bih=Z.height;qa.biw=Z.width;qa.brdim=p.join();
b=b.i;b=(qa.vis=b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,qa.wgl=!!Fh.WebGLRenderingContext,qa);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var fl=new function(){var a=window.document;this.h=window;this.i=a};
D("yt.ads_.signals_.getAdSignalsString",function(a){return $k(el(a))});Wa();navigator.userAgent.indexOf(" (CrKey ");function S(a){a=gl(a);return"string"===typeof a&&"false"===a?!1:!!a}
function hl(a,b){a=gl(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function gl(a){var b=R("EXPERIMENTS_FORCED_FLAGS",{})||{};return void 0!==b[a]?b[a]:R("EXPERIMENT_FLAGS",{})[a]}
function il(){for(var a=[],b=R("EXPERIMENTS_FORCED_FLAGS",{}),c=v(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=R("EXPERIMENT_FLAGS",{});var e=v(Object.keys(c));for(d=e.next();!d.done;d=e.next())d=d.value,d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var jl="XMLHttpRequest"in C?function(){return new XMLHttpRequest}:null;
function kl(){if(!jl)return null;var a=jl();return"open"in a?a:null}
function ll(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function ml(a,b){"function"===typeof a&&(a=Sk(a));return window.setTimeout(a,b)}
;var nl="client_dev_domain client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");[].concat(ja(nl),["client_dev_set_cookie"]);var ol={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},pl="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ja(nl)),ql=!1;
function rl(a,b){b=void 0===b?{}:b;var c=dl(a),d=S("web_ajax_ignore_global_headers_if_set"),e;for(e in ol){var f=R(ol[e]),g="X-Goog-AuthUser"===e||"X-Goog-PageId"===e;"X-Goog-Visitor-Id"!==e||f||(f=R("VISITOR_DATA"));!f||!c&&cc(a)||d&&void 0!==b[e]||"TVHTML5_UNPLUGGED"===R("INNERTUBE_CLIENT_NAME")&&g||(b[e]=f)}c&&R("SESSION_INDEX")&&"TVHTML5_UNPLUGGED"!==R("INNERTUBE_CLIENT_NAME")&&(b["X-Yt-Auth-Test"]="test");"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||
!cc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!cc(a)){try{var h=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(k){}h&&(b["X-YouTube-Time-Zone"]=h)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&cc(a)||(b["X-YouTube-Ad-Signals"]=$k(el()));return b}
function sl(a){var b=window.location.search,c=cc(a);S("debug_handle_relative_url_for_query_forward_killswitch")||!c&&dl(a)&&(c=document.location.hostname);var d=ac(bc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=al(b),f={};db(pl,function(g){e[g]&&(f[g]=e[g])});
return cl(a,f||{},!1)}
function tl(a,b){var c=b.format||"JSON";a=ul(a,b);var d=vl(a,b),e=!1,f=wl(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var l=ll(k),n=null,r=400<=k.status&&500>k.status,t=500<=k.status&&600>k.status;if(l||r||t)n=xl(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(n&&n.return_code,10);break a;case "RAW":l=!0;break a}l=!!n}n=n||{};r=b.context||C;l?b.onSuccess&&b.onSuccess.call(r,k,n):b.onError&&b.onError.call(r,k,n);b.onFinish&&b.onFinish.call(r,
k,n)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=ml(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||C,f))},d)}return f}
function ul(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=R("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=cl(a,b||{},!0);return a}
function vl(a,b){var c=R("XSRF_FIELD_NAME"),d=R("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=R("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||cc(a)&&!b.withCredentials&&cc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(S("ajax_parse_query_data_only_when_filled")&&f&&0<Object.keys(f).length||f)&&"string"===typeof e&&(e=al(e),ub(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?
JSON.stringify(e):jc(e));f=e||f&&!nb(f);!ql&&f&&"POST"!=b.method&&(ql=!0,Tk(Error("AJAX request with postData should use POST")));return e}
function xl(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Uk(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?yl(a):null)e={},db(a.getElementsByTagName("*"),function(g){e[g.tagName]=zl(g)})}d&&Al(e);
return e}
function Al(a){if(Oa(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b],e=wb();d=e?e.createHTML(d):d;a[c]=new Wb(d)}else Al(a[b])}}
function yl(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function zl(a){var b="";db(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Bl(a,b){b.method="POST";b.postParams||(b.postParams={});return tl(a,b)}
function wl(a,b,c,d,e,f,g,h){function k(){4==(l&&"readyState"in l?l.readyState:0)&&b&&Sk(b)(l)}
c=void 0===c?"GET":c;d=void 0===d?"":d;h=void 0===h?!1:h;var l=kl();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",k,!1):l.onreadystatechange=k;S("debug_forward_web_query_parameters")&&(a=sl(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=rl(a,e))for(var n in e)l.setRequestHeader(n,e[n]),"content-type"==n.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");
h&&"setAttributionReporting"in XMLHttpRequest.prototype&&l.setAttributionReporting({eventSourceEligible:!0,triggerEligible:!1});l.send(d);return l}
;var Cl=[{Nc:function(a){return"Cannot read property '"+a.key+"'"},
mc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Nc:function(a){return"Cannot call '"+a.key+"'"},
mc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Nc:function(a){return a.key+" is not defined"},
mc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var El={Va:[],Sa:[{callback:Dl,weight:500}]};function Dl(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Fl(){this.Sa=[];this.Va=[]}
var Gl;function Hl(){if(!Gl){var a=Gl=new Fl;a.Va.length=0;a.Sa.length=0;El.Va&&a.Va.push.apply(a.Va,El.Va);El.Sa&&a.Sa.push.apply(a.Sa,El.Sa)}return Gl}
;var Il=new L;function Jl(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Kl(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=Kl(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=Kl(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function Kl(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function Ll(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Ml(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=Jl(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?Ml(e+".ve",f,g,h):0;d+=g;d+=Ml(e,a[e],b,c);if(500<d)break}}else c[b]=Nl(a),d+=c[b].length;else c[b]=Nl(a),d+=c[b].length;return d}
function Ml(a,b,c,d){c+="."+a;a=Nl(b);d[c]=a;return c.length+a.length}
function Nl(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function Ol(){this.cf=!0}
function Pl(){Ol.h||(Ol.h=new Ol);return Ol.h}
function Ql(a,b){a={};var c=xg([]);c&&(a.Authorization=c,c=b=null==b?void 0:b.sessionIndex,void 0===c&&(c=Number(R("SESSION_INDEX",0)),c=isNaN(c)?0:c),S("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in Nk||(a["X-Origin"]=window.location.origin),void 0===b&&"DELEGATED_SESSION_ID"in Nk&&(a["X-Goog-PageId"]=R("DELEGATED_SESSION_ID")));return a}
;var Rl={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function Sl(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function Tl(){if(!C.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return C.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":C.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":C.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":C.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function Ul(a,b,c,d,e){tg.set(""+a,b,{ic:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function Vl(a){return tg.get(""+a,void 0)}
function Wl(a,b,c){tg.remove(""+a,void 0===b?"/":b,void 0===c?"youtube.com":c)}
function Xl(){if(!tg.isEnabled())return!1;if(!tg.isEmpty())return!0;tg.set("TESTCOOKIESENABLED","1",{ic:60});if("1"!==tg.get("TESTCOOKIESENABLED"))return!1;tg.remove("TESTCOOKIESENABLED");return!0}
;var Yl=E("ytglobal.prefsUserPrefsPrefs_")||{};D("ytglobal.prefsUserPrefsPrefs_",Yl);function Zl(){this.h=R("ALT_PREF_COOKIE_NAME","PREF");this.i=R("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=Vl(this.h);a&&this.parse(a)}
var $l;function am(){$l||($l=new Zl);return $l}
m=Zl.prototype;m.get=function(a,b){bm(a);cm(a);a=void 0!==Yl[a]?Yl[a].toString():null;return null!=a?a:b?b:""};
m.set=function(a,b){bm(a);cm(a);if(null==b)throw Error("ExpectedNotNull");Yl[a]=b.toString()};
function dm(a){return!!((em("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
m.remove=function(a){bm(a);cm(a);delete Yl[a]};
m.clear=function(){for(var a in Yl)delete Yl[a]};
function cm(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function bm(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function em(a){a=void 0!==Yl[a]?Yl[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
m.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(Yl[d]=c.toString())}};var fm={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},gm={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function hm(){var a=C.navigator;return a?a.connection:void 0}
function im(){var a=hm();if(a){var b=fm[a.type||"unknown"]||"CONN_UNKNOWN";a=fm[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function jm(){var a=hm();if(null!=a&&a.effectiveType)return gm.hasOwnProperty(a.effectiveType)?gm[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function km(a){var b=B.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ja(b))}
w(km,Error);function lm(){try{return mm(),!0}catch(a){return!1}}
function mm(a){if(void 0!==R("DATASYNC_ID"))return R("DATASYNC_ID");throw new km("Datasync ID not set",void 0===a?"unknown":a);}
;function nm(){}
function om(a,b){return pi.bb(a,0,b)}
nm.prototype.oa=function(a,b){return this.bb(a,1,b)};
nm.prototype.Kb=function(a){var b=E("yt.scheduler.instance.addImmediateJob");b?b(a):a()};var pm=hl("web_emulated_idle_callback_delay",300),qm=1E3/60-3,rm=[8,5,4,3,2,1,0];
function sm(a){a=void 0===a?{}:a;G.call(this);this.i=[];this.j={};this.Y=this.h=0;this.W=this.m=!1;this.R=[];this.S=this.da=!1;for(var b=v(rm),c=b.next();!c.done;c=b.next())this.i[c.value]=[];this.l=0;this.xc=a.timeout||1;this.D=qm;this.s=0;this.ma=this.Ge.bind(this);this.wc=this.ff.bind(this);this.Ba=this.Vd.bind(this);this.Ja=this.qe.bind(this);this.qb=this.Ie.bind(this);this.na=!!window.requestIdleCallback&&!!window.cancelIdleCallback&&!S("disable_scheduler_requestIdleCallback");(this.ea=!1!==
a.useRaf&&!!window.requestAnimationFrame)&&document.addEventListener("visibilitychange",this.ma)}
w(sm,G);m=sm.prototype;m.Kb=function(a){var b=Wa();tm(this,a);a=Wa()-b;this.m||(this.D-=a)};
m.bb=function(a,b,c){++this.Y;if(10===b)return this.Kb(a),this.Y;var d=this.Y;this.j[d]=a;this.m&&!c?this.R.push({id:d,priority:b}):(this.i[b].push(d),this.W||this.m||(0!==this.h&&um(this)!==this.s&&this.stop(),this.start()));return d};
m.qa=function(a){delete this.j[a]};
function wm(a){a.R.length=0;for(var b=5;0<=b;b--)a.i[b].length=0;a.i[8].length=0;a.j={};a.stop()}
m.isHidden=function(){return!!document.hidden||!1};
function xm(a){return!a.isHidden()&&a.ea}
function um(a){if(a.i[8].length){if(a.S)return 4;if(xm(a))return 3}for(var b=5;b>=a.l;b--)if(0<a.i[b].length)return 0<b?xm(a)?3:2:1;return 0}
m.Rb=function(a){var b=E("yt.logging.errors.log");b&&b(a)};
function tm(a,b){try{b()}catch(c){a.Rb(c)}}
function ym(a){for(var b=v(rm),c=b.next();!c.done;c=b.next())if(a.i[c.value].length)return!0;return!1}
m.qe=function(a){var b=void 0;a&&(b=a.timeRemaining());this.da=!0;zm(this,b);this.da=!1};
m.ff=function(){zm(this)};
m.Vd=function(){Am(this)};
m.Ie=function(a){this.S=!0;var b=um(this);4===b&&b!==this.s&&(this.stop(),this.start());zm(this,void 0,a);this.S=!1};
m.Ge=function(){this.isHidden()||Am(this);this.h&&(this.stop(),this.start())};
function Am(a){a.stop();a.m=!0;for(var b=Wa(),c=a.i[8];c.length;){var d=c.shift(),e=a.j[d];delete a.j[d];e&&tm(a,e)}Bm(a);a.m=!1;ym(a)&&a.start();b=Wa()-b;a.D-=b}
function Bm(a){for(var b=0,c=a.R.length;b<c;b++){var d=a.R[b];a.i[d.priority].push(d.id)}a.R.length=0}
function zm(a,b,c){a.S&&4===a.s&&a.h||a.stop();a.m=!0;b=Wa()+(b||a.D);for(var d=a.i[5];d.length;){var e=d.shift(),f=a.j[e];delete a.j[e];if(f){e=a;try{f(c)}catch(l){e.Rb(l)}}}for(d=a.i[4];d.length;)c=d.shift(),f=a.j[c],delete a.j[c],f&&tm(a,f);d=a.da?0:1;d=a.l>d?a.l:d;if(!(Wa()>=b)){do{a:{c=a;f=d;for(e=3;e>=f;e--)for(var g=c.i[e];g.length;){var h=g.shift(),k=c.j[h];delete c.j[h];if(k){c=k;break a}}c=null}c&&tm(a,c)}while(c&&Wa()<b)}a.m=!1;Bm(a);a.D=qm;ym(a)&&a.start()}
m.start=function(){this.W=!1;if(0===this.h)switch(this.s=um(this),this.s){case 1:var a=this.Ja;this.h=this.na?window.requestIdleCallback(a,{timeout:3E3}):window.setTimeout(a,pm);break;case 2:this.h=window.setTimeout(this.wc,this.xc);break;case 3:this.h=window.requestAnimationFrame(this.qb);break;case 4:this.h=window.setTimeout(this.Ba,0)}};
m.pause=function(){this.stop();this.W=!0};
m.stop=function(){if(this.h){switch(this.s){case 1:var a=this.h;this.na?window.cancelIdleCallback(a):window.clearTimeout(a);break;case 2:case 4:window.clearTimeout(this.h);break;case 3:window.cancelAnimationFrame(this.h)}this.h=0}};
m.M=function(){wm(this);this.stop();this.ea&&document.removeEventListener("visibilitychange",this.ma);G.prototype.M.call(this)};var Cm=E("yt.scheduler.instance.timerIdMap_")||{},Dm=hl("kevlar_tuner_scheduler_soft_state_timer_ms",800),Em=0,Fm=0;function Gm(){var a=E("ytglobal.schedulerInstanceInstance_");if(!a||a.Z())a=new sm(R("scheduler")||{}),D("ytglobal.schedulerInstanceInstance_",a);return a}
function Hm(){Im();var a=E("ytglobal.schedulerInstanceInstance_");a&&(vc(a),D("ytglobal.schedulerInstanceInstance_",null))}
function Im(){wm(Gm());for(var a in Cm)Cm.hasOwnProperty(a)&&delete Cm[Number(a)]}
function Jm(a,b,c){if(!c)return c=void 0===c,-Gm().bb(a,b,c);var d=window.setTimeout(function(){var e=Gm().bb(a,b);Cm[d]=e},c);
return d}
function Km(a){Gm().Kb(a)}
function Lm(a){var b=Gm();if(0>a)b.qa(-a);else{var c=Cm[a];c?(b.qa(c),delete Cm[a]):window.clearTimeout(a)}}
function Mm(){Nm()}
function Nm(){window.clearTimeout(Em);Gm().start()}
function Om(){Gm().pause();window.clearTimeout(Em);Em=window.setTimeout(Mm,Dm)}
function Pm(){window.clearTimeout(Fm);Fm=window.setTimeout(function(){Qm(0)},Dm)}
function Qm(a){Pm();var b=Gm();b.l=a;b.start()}
function Rm(a){Pm();var b=Gm();b.l>a&&(b.l=a,b.start())}
function Sm(){window.clearTimeout(Fm);var a=Gm();a.l=0;a.start()}
;function Tm(){nm.apply(this,arguments)}
w(Tm,nm);function Um(){Tm.h||(Tm.h=new Tm);return Tm.h}
Tm.prototype.bb=function(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=E("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):ml(a,c||0)};
Tm.prototype.qa=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=E("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
Tm.prototype.start=function(){var a=E("yt.scheduler.instance.start");a&&a()};
Tm.prototype.pause=function(){var a=E("yt.scheduler.instance.pause");a&&a()};
var pi=Um();
S("web_scheduler_auto_init")&&!E("yt.scheduler.initialized")&&(D("yt.scheduler.instance.dispose",Hm),D("yt.scheduler.instance.addJob",Jm),D("yt.scheduler.instance.addImmediateJob",Km),D("yt.scheduler.instance.cancelJob",Lm),D("yt.scheduler.instance.cancelAllJobs",Im),D("yt.scheduler.instance.start",Nm),D("yt.scheduler.instance.pause",Om),D("yt.scheduler.instance.setPriorityThreshold",Qm),D("yt.scheduler.instance.enablePriorityThreshold",Rm),D("yt.scheduler.instance.clearPriorityThreshold",Sm),D("yt.scheduler.initialized",
!0));function Vm(a){var b=new Vi;(b=b.isAvailable()?a?new aj(b,a):b:null)||(a=new Wi(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new Ri(a):null;this.i=document.domain||window.location.hostname}
Vm.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape((new bh).serialize(b))}catch(f){return}else e=escape(b);Ul(a,e,c,this.i)};
Vm.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=Vl(a))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Vm.prototype.remove=function(a){this.h&&this.h.remove(a);Wl(a,"/",this.i)};var Wm=function(){var a;return function(){a||(a=new Vm("ytidb"));return a}}();
function Xm(){var a;return null==(a=Wm())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var Ym=[],Zm,$m=!1;function an(){var a={};for(Zm=new bn(void 0===a.handleError?cn:a.handleError,void 0===a.logEvent?dn:a.logEvent);0<Ym.length;)switch(a=Ym.shift(),a.type){case "ERROR":Zm.Rb(a.payload);break;case "EVENT":Zm.logEvent(a.eventType,a.payload)}}
function en(a){$m||(Zm?Zm.Rb(a):(Ym.push({type:"ERROR",payload:a}),10<Ym.length&&Ym.shift()))}
function fn(a,b){$m||(Zm?Zm.logEvent(a,b):(Ym.push({type:"EVENT",eventType:a,payload:b}),10<Ym.length&&Ym.shift()))}
;function gn(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function hn(a){return a.substr(0,a.indexOf(":"))||a}
;var jn=Ae||Be;function kn(a){var b=Nb();return b?0<=b.toLowerCase().indexOf(a):!1}
;var ln={},mn=(ln.AUTH_INVALID="No user identifier specified.",ln.EXPLICIT_ABORT="Transaction was explicitly aborted.",ln.IDB_NOT_SUPPORTED="IndexedDB is not supported.",ln.MISSING_INDEX="Index not created.",ln.MISSING_OBJECT_STORES="Object stores not created.",ln.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",ln.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",ln.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
ln.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",ln.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",ln.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",ln.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",ln),nn={},on=(nn.AUTH_INVALID="ERROR",nn.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",nn.EXPLICIT_ABORT="IGNORED",nn.IDB_NOT_SUPPORTED="ERROR",nn.MISSING_INDEX=
"WARNING",nn.MISSING_OBJECT_STORES="ERROR",nn.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",nn.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",nn.QUOTA_EXCEEDED="WARNING",nn.QUOTA_MAYBE_EXCEEDED="WARNING",nn.UNKNOWN_ABORT="WARNING",nn.INCOMPATIBLE_DB_VERSION="WARNING",nn),pn={},qn=(pn.AUTH_INVALID=!1,pn.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,pn.EXPLICIT_ABORT=!1,pn.IDB_NOT_SUPPORTED=!1,pn.MISSING_INDEX=!1,pn.MISSING_OBJECT_STORES=!1,pn.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,pn.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,pn.QUOTA_EXCEEDED=!1,pn.QUOTA_MAYBE_EXCEEDED=!0,pn.UNKNOWN_ABORT=!0,pn.INCOMPATIBLE_DB_VERSION=!1,pn);function rn(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?mn[a]:c;d=void 0===d?on[a]:d;e=void 0===e?qn[a]:e;km.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,rn.prototype)}
w(rn,km);function sn(a,b){rn.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},mn.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,sn.prototype)}
w(sn,rn);function tn(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,tn.prototype)}
w(tn,Error);var un=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function vn(a,b,c,d){b=hn(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof rn)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new rn("QUOTA_EXCEEDED",a);if(Ce&&"UnknownError"===e.name)return new rn("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof tn)return new rn("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&un.some(function(f){return e.message.includes(f)}))return new rn("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new rn("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",yd:e.name})];e.level="WARNING";return e}
function wn(a,b,c){var d=Xm();return new rn("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function xn(a){if(!a)throw Error();throw a;}
function yn(a){return a}
function zn(a){this.h=a}
function An(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=v(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=v(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
An.all=function(a){return new An(new zn(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={zb:0};f.zb<a.length;f={zb:f.zb},++f.zb)An.resolve(a[f.zb]).then(function(g){return function(h){d[g.zb]=h;e--;0===e&&b(d)}}(f)).catch(function(g){c(g)})}))};
An.resolve=function(a){return new An(new zn(function(b,c){a instanceof An?a.then(b,c):b(a)}))};
An.reject=function(a){return new An(new zn(function(b,c){c(a)}))};
An.prototype.then=function(a,b){var c=this,d=null!=a?a:yn,e=null!=b?b:xn;return new An(new zn(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){Bn(c,c,d,f,g)}),c.i.push(function(){Cn(c,c,e,f,g)})):"FULFILLED"===c.state.status?Bn(c,c,d,f,g):"REJECTED"===c.state.status&&Cn(c,c,e,f,g)}))};
An.prototype.catch=function(a){return this.then(void 0,a)};
function Bn(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof An?Dn(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Cn(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof An?Dn(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Dn(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof An?Dn(a,b,f,d,e):d(f)},function(f){e(f)})}
;function En(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Fn(a){return new Promise(function(b,c){En(a,b,c)})}
function Gn(a){return new An(new zn(function(b,c){En(a,b,c)}))}
;function Hn(a,b){return new An(new zn(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var In=window,T=In.ytcsi&&In.ytcsi.now?In.ytcsi.now:In.performance&&In.performance.timing&&In.performance.now&&In.performance.timing.navigationStart?function(){return In.performance.timing.navigationStart+In.performance.now()}:function(){return(new Date).getTime()};function Jn(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(T());this.i=!1}
m=Jn.prototype;m.add=function(a,b,c){return Kn(this,[a],{mode:"readwrite",ha:!0},function(d){return d.objectStore(a).add(b,c)})};
m.clear=function(a){return Kn(this,[a],{mode:"readwrite",ha:!0},function(b){return b.objectStore(a).clear()})};
m.close=function(){this.h.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
m.count=function(a,b){return Kn(this,[a],{mode:"readonly",ha:!0},function(c){return c.objectStore(a).count(b)})};
function Ln(a,b,c){a=a.h.createObjectStore(b,c);return new Mn(a)}
m.delete=function(a,b){return Kn(this,[a],{mode:"readwrite",ha:!0},function(c){return c.objectStore(a).delete(b)})};
m.get=function(a,b){return Kn(this,[a],{mode:"readonly",ha:!0},function(c){return c.objectStore(a).get(b)})};
function Nn(a,b,c){return Kn(a,[b],{mode:"readwrite",ha:!0},function(d){d=d.objectStore(b);return Gn(d.h.put(c,void 0))})}
m.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function Kn(a,b,c,d){var e,f,g,h,k,l,n,r,t,p,x,y;return A(function(z){switch(z.h){case 1:var H={mode:"readonly",ha:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?H.mode=c:Object.assign(H,c);e=H;a.transactionCount++;f=e.ha?3:1;g=0;case 2:if(h){z.v(4);break}g++;k=Math.round(T());za(z,5);l=a.h.transaction(b,e.mode);H=z.yield;var I=new On(l);I=Pn(I,d);return H.call(z,I,7);case 7:return n=z.i,r=Math.round(T()),Qn(a,k,r,g,void 0,b.join(),e),z.return(n);case 5:t=Aa(z);p=Math.round(T());x=vn(t,
a.h.name,b.join(),a.h.version);if((y=x instanceof rn&&!x.h)||g>=f)Qn(a,k,p,g,x,b.join(),e),h=x;z.v(2);break;case 4:return z.return(Promise.reject(h))}})}
function Qn(a,b,c,d,e,f,g){b=c-b;e?(e instanceof rn&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&fn("QUOTA_EXCEEDED",{dbName:hn(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof rn&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),fn("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),Rn(a,!1,d,f,b,g.tag),en(e)):Rn(a,!0,d,f,b,g.tag)}
function Rn(a,b,c,d,e,f){fn("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
m.getName=function(){return this.h.name};
function Mn(a){this.h=a}
m=Mn.prototype;m.add=function(a,b){return Gn(this.h.add(a,b))};
m.autoIncrement=function(){return this.h.autoIncrement};
m.clear=function(){return Gn(this.h.clear()).then(function(){})};
function Sn(a,b,c){a.h.createIndex(b,c,{unique:!1})}
m.count=function(a){return Gn(this.h.count(a))};
function Tn(a,b){return Un(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
m.delete=function(a){return a instanceof IDBKeyRange?Tn(this,a):Gn(this.h.delete(a))};
m.get=function(a){return Gn(this.h.get(a))};
m.index=function(a){try{return new Vn(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new tn(a,this.h.name);throw b;}};
m.getName=function(){return this.h.name};
m.keyPath=function(){return this.h.keyPath};
function Un(a,b,c){a=a.h.openCursor(b.query,b.direction);return Wn(a).then(function(d){return Hn(d,c)})}
function On(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=rn;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function Pn(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return v(d).next().value})}
On.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new rn("EXPLICIT_ABORT");};
On.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.i.get(a);b||(b=new Mn(a),this.i.set(a,b));return b};
function Vn(a){this.h=a}
m=Vn.prototype;m.count=function(a){return Gn(this.h.count(a))};
m.delete=function(a){return Xn(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
m.get=function(a){return Gn(this.h.get(a))};
m.getKey=function(a){return Gn(this.h.getKey(a))};
m.keyPath=function(){return this.h.keyPath};
m.unique=function(){return this.h.unique};
function Xn(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Wn(a).then(function(d){return Hn(d,c)})}
function Yn(a,b){this.request=a;this.cursor=b}
function Wn(a){return Gn(a).then(function(b){return b?new Yn(a,b):null})}
m=Yn.prototype;m.advance=function(a){this.cursor.advance(a);return Wn(this.request)};
m.continue=function(a){this.cursor.continue(a);return Wn(this.request)};
m.delete=function(){return Gn(this.cursor.delete()).then(function(){})};
m.getKey=function(){return this.cursor.key};
m.getValue=function(){return this.cursor.value};
m.update=function(a){return Gn(this.cursor.update(a))};function Zn(a,b,c){return new Promise(function(d,e){function f(){t||(t=new Jn(g.result,{closed:r}));return t}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.Xd,k=c.blocking,l=c.df,n=c.upgrade,r=c.closed,t;g.addEventListener("upgradeneeded",function(p){try{if(null===p.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");p.dataLoss&&"none"!==p.dataLoss&&fn("IDB_DATA_CORRUPTED",{reason:p.dataLossMessage||"unknown reason",dbName:hn(a)});var x=f(),y=new On(g.transaction);
n&&n(x,function(z){return p.oldVersion<z&&p.newVersion>=z},y);
y.done.catch(function(z){e(z)})}catch(z){e(z)}});
g.addEventListener("success",function(){var p=g.result;k&&p.addEventListener("versionchange",function(){k(f())});
p.addEventListener("close",function(){fn("IDB_UNEXPECTEDLY_CLOSED",{dbName:hn(a),dbVersion:p.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function $n(a,b,c){c=void 0===c?{}:c;return Zn(a,b,c)}
function ao(a,b){b=void 0===b?{}:b;var c,d,e,f;return A(function(g){if(1==g.h)return za(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.Xd)&&c.addEventListener("blocked",function(){e()}),g.yield(Fn(c),4);
if(2!=g.h)g.h=0,g.l=0;else throw f=Aa(g),vn(f,a,"",-1);})}
;function bo(a,b){this.name=a;this.options=b;this.j=!0;this.m=this.l=0}
bo.prototype.i=function(a,b,c){c=void 0===c?{}:c;return $n(a,b,c)};
bo.prototype.delete=function(a){a=void 0===a?{}:a;return ao(this.name,a)};
function co(a,b){return new rn("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function eo(a,b){if(!b)throw wn("openWithToken",hn(a.name));return a.open()}
bo.prototype.open=function(){function a(){var f,g,h,k,l,n,r,t,p,x;return A(function(y){switch(y.h){case 1:return g=null!=(f=Error().stack)?f:"",za(y,2),y.yield(c.i(c.name,c.options.version,e),4);case 4:h=y.i;for(var z=c.options,H=[],I=v(Object.keys(z.Gb)),M=I.next();!M.done;M=I.next()){M=M.value;var N=z.Gb[M],K=void 0===N.Le?Number.MAX_VALUE:N.Le;!(h.h.version>=N.Lb)||h.h.version>=K||h.h.objectStoreNames.contains(M)||H.push(M)}k=H;if(0===k.length){y.v(5);break}l=Object.keys(c.options.Gb);n=h.objectStoreNames();
if(c.m<hl("ytidb_reopen_db_retries",0))return c.m++,h.close(),en(new rn("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:n})),y.return(a());if(!(c.l<hl("ytidb_remake_db_retries",1))){y.v(6);break}c.l++;return y.yield(c.delete(),7);case 7:return en(new rn("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:n})),y.return(a());case 6:throw new sn(n,l);case 5:return y.return(h);case 2:r=Aa(y);if(r instanceof DOMException?
"VersionError"!==r.name:"DOMError"in self&&r instanceof DOMError?"VersionError"!==r.name:!(r instanceof Object&&"message"in r)||"An attempt was made to open a database using a lower version than the existing version."!==r.message){y.v(8);break}return y.yield(c.i(c.name,void 0,Object.assign({},e,{upgrade:void 0})),9);case 9:t=y.i;p=t.h.version;if(void 0!==c.options.version&&p>c.options.version+1)throw t.close(),c.j=!1,co(c,p);return y.return(t);case 8:throw b(),r instanceof Error&&!S("ytidb_async_stack_killswitch")&&
(r.stack=r.stack+"\n"+g.substring(g.indexOf("\n")+1)),vn(r,c.name,"",null!=(x=c.options.version)?x:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.j)throw co(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,df:b,upgrade:this.options.upgrade};return this.h=d=a()};var fo=new bo("YtIdbMeta",{Gb:{databases:{Lb:1}},upgrade:function(a,b){b(1)&&Ln(a,"databases",{keyPath:"actualName"})}});
function go(a,b){var c;return A(function(d){if(1==d.h)return d.yield(eo(fo,b),2);c=d.i;return d.return(Kn(c,["databases"],{ha:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Gn(f.h.put(a,void 0)).then(function(){})})}))})}
function ho(a,b){var c;return A(function(d){if(1==d.h)return a?d.yield(eo(fo,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function io(a,b){var c,d;return A(function(e){return 1==e.h?(c=[],e.yield(eo(fo,b),2)):3!=e.h?(d=e.i,e.yield(Kn(d,["databases"],{ha:!0,mode:"readonly"},function(f){c.length=0;return Un(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function jo(a){return io(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function ko(a,b,c){return io(function(d){return c?void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)},b)}
function lo(a){var b,c;return A(function(d){if(1==d.h)return b=mm("YtIdbMeta hasAnyMeta other"),d.yield(io(function(e){return void 0!==e.userIdentifier&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(0<c.length)})}
;var mo,no=new function(){}(new function(){});
function oo(){var a,b,c,d;return A(function(e){switch(e.h){case 1:a=Xm();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=jn)f=/WebKit\/([0-9]+)/.exec(Nb()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Nb()),f=!(f&&602<=parseInt(f[1],10)));if(f||Kc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
za(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return e.yield(go(d,no),4);case 4:return e.yield(ho("yt-idb-test-do-not-use",no),5);case 5:return e.return(!0);case 2:return Aa(e),e.return(!1)}})}
function po(){if(void 0!==mo)return mo;$m=!0;return mo=oo().then(function(a){$m=!1;var b;if(null!=(b=Wm())&&b.h){var c;b={hasSucceededOnce:(null==(c=Xm())?void 0:c.hasSucceededOnce)||a};var d;null==(d=Wm())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function qo(){return E("ytglobal.idbToken_")||void 0}
function ro(){var a=qo();return a?Promise.resolve(a):po().then(function(b){(b=b?no:void 0)&&D("ytglobal.idbToken_",b);return b})}
;var so=0;function to(a,b){so||(so=pi.oa(function(){var c,d,e,f,g;return A(function(h){switch(h.h){case 1:return h.yield(ro(),2);case 2:c=h.i;if(!c)return h.return();d=!0;za(h,3);return h.yield(ko(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.v(6);break}f=e[0];return h.yield(ao(f.actualName),7);case 7:return h.yield(ho(f.actualName,c),6);case 6:h.h=4;h.l=0;break;case 3:g=Aa(h),en(g),d=!1;case 4:pi.qa(so),so=0,d&&to(a,b),h.h=0}})}))}
function uo(){var a;return A(function(b){return 1==b.h?b.yield(ro(),2):(a=b.i)?b.return(lo(a)):b.return(!1)})}
new Dh;function vo(a){if(!lm())throw a=new rn("AUTH_INVALID",{dbName:a}),en(a),a;var b=mm();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function wo(a,b,c,d){var e,f,g,h,k,l;return A(function(n){switch(n.h){case 1:return f=null!=(e=Error().stack)?e:"",n.yield(ro(),2);case 2:g=n.i;if(!g)throw h=wn("openDbImpl",a,b),S("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),en(h),h;gn(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:vo(a);za(n,3);return n.yield(go(k,g),5);case 5:return n.yield($n(k.actualName,b,d),6);case 6:return n.return(n.i);case 3:return l=Aa(n),za(n,7),n.yield(ho(k.actualName,
g),9);case 9:n.h=8;n.l=0;break;case 7:Aa(n);case 8:throw l;}})}
function xo(a,b,c){c=void 0===c?{}:c;return wo(a,b,!1,c)}
function yo(a,b,c){c=void 0===c?{}:c;return wo(a,b,!0,c)}
function zo(a,b){b=void 0===b?{}:b;var c,d;return A(function(e){if(1==e.h)return e.yield(ro(),2);if(3!=e.h){c=e.i;if(!c)return e.return();gn(a);d=vo(a);return e.yield(ao(d.actualName,b),3)}return e.yield(ho(d.actualName,c),0)})}
function Ao(a,b,c){a=a.map(function(d){return A(function(e){return 1==e.h?e.yield(ao(d.actualName,b),2):e.yield(ho(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Bo(){var a=void 0===a?{}:a;var b,c;return A(function(d){if(1==d.h)return d.yield(ro(),2);if(3!=d.h){b=d.i;if(!b)return d.return();gn("LogsDatabaseV2");return d.yield(jo(b),3)}c=d.i;return d.yield(Ao(c,a,b),0)})}
function Co(a,b){b=void 0===b?{}:b;var c;return A(function(d){if(1==d.h)return d.yield(ro(),2);if(3!=d.h){c=d.i;if(!c)return d.return();gn(a);return d.yield(ao(a,b),3)}return d.yield(ho(a,c),0)})}
;function Do(a,b){bo.call(this,a,b);this.options=b;gn(a)}
w(Do,bo);function Eo(a,b){var c;return function(){c||(c=new Do(a,b));return c}}
Do.prototype.i=function(a,b,c){c=void 0===c?{}:c;return(this.options.sc?yo:xo)(a,b,Object.assign({},c))};
Do.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.sc?Co:zo)(this.name,a)};
function Fo(a,b){return Eo(a,b)}
;var Go={},Ho=Fo("ytGcfConfig",{Gb:(Go.coldConfigStore={Lb:1},Go.hotConfigStore={Lb:1},Go),sc:!1,upgrade:function(a,b){b(1)&&(Sn(Ln(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),Sn(Ln(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function Io(a){return eo(Ho(),a)}
function Jo(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:T()},g.yield(Io(c),2);case 2:return e=g.i,g.yield(e.clear("hotConfigStore"),3);case 3:return g.yield(Nn(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function Ko(a,b,c,d){var e,f,g;return A(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:T()},h.yield(Io(d),2);case 2:return f=h.i,h.yield(f.clear("coldConfigStore"),3);case 3:return h.yield(Nn(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function Lo(a){var b,c;return A(function(d){return 1==d.h?d.yield(Io(a),2):3!=d.h?(b=d.i,c=void 0,d.yield(Kn(b,["coldConfigStore"],{mode:"readwrite",ha:!0},function(e){return Xn(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function Mo(a){var b,c;return A(function(d){return 1==d.h?d.yield(Io(a),2):3!=d.h?(b=d.i,c=void 0,d.yield(Kn(b,["hotConfigStore"],{mode:"readwrite",ha:!0},function(e){return Xn(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function No(){G.call(this);this.i=[];this.h=[];var a=E("yt.gcf.config.hotUpdateCallbacks");a?(this.i=[].concat(ja(a)),this.h=a):(this.h=[],D("yt.gcf.config.hotUpdateCallbacks",this.h))}
w(No,G);No.prototype.M=function(){for(var a=v(this.i),b=a.next();!b.done;b=a.next()){var c=this.h;b=c.indexOf(b.value);0<=b&&c.splice(b,1)}this.i.length=0;G.prototype.M.call(this)};function Oo(){this.h=0;this.i=new No}
function Po(){var a;return null!=(a=E("yt.gcf.config.hotConfigGroup"))?a:null}
function Qo(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:if(!S("start_client_gcf")){g.v(0);break}c&&(a.j=c,D("yt.gcf.config.hotConfigGroup",a.j||null));a.l(b);d=qo();if(!d){g.v(3);break}if(c){g.v(4);break}return g.yield(Mo(d),5);case 5:e=g.i,c=null==(f=e)?void 0:f.config;case 4:return g.yield(Jo(c,b,d),3);case 3:if(c)for(var h=c,k=v(a.i.h),l=k.next();!l.done;l=k.next())l=l.value,l(h);g.h=0}})}
function Ro(a,b,c){var d,e,f,g;return A(function(h){if(1==h.h){if(!S("start_client_gcf"))return h.v(0);a.coldHashData=b;D("yt.gcf.config.coldHashData",a.coldHashData||null);return(d=qo())?c?h.v(4):h.yield(Lo(d),5):h.v(0)}4!=h.h&&(e=h.i,c=null==(f=e)?void 0:f.config);if(!c)return h.v(0);g=c.configData;return h.yield(Ko(c,b,g,d),0)})}
function So(){if(!Oo.h){var a=new Oo;Oo.h=a}a=Oo.h;var b=T()-a.h;if(!(0!==a.h&&b<hl("send_config_hash_timer"))){b=E("yt.gcf.config.coldConfigData");var c=E("yt.gcf.config.hotHashData"),d=E("yt.gcf.config.coldHashData");b&&c&&d&&(a.h=T());return{coldConfigData:b,hotHashData:c,coldHashData:d}}}
Oo.prototype.l=function(a){this.hotHashData=a;D("yt.gcf.config.hotHashData",this.hotHashData||null)};function To(){return"INNERTUBE_API_KEY"in Nk&&"INNERTUBE_API_VERSION"in Nk}
function Uo(){return{innertubeApiKey:R("INNERTUBE_API_KEY"),innertubeApiVersion:R("INNERTUBE_API_VERSION"),re:R("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),sd:R("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Uf:R("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:R("INNERTUBE_CONTEXT_CLIENT_VERSION"),te:R("INNERTUBE_CONTEXT_HL"),se:R("INNERTUBE_CONTEXT_GL"),ue:R("INNERTUBE_HOST_OVERRIDE")||"",xe:!!R("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),we:!!R("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:R("SERIALIZED_CLIENT_CONFIG_DATA")}}
function Vo(a){var b={client:{hl:a.te,gl:a.se,clientName:a.sd,clientVersion:a.innertubeContextClientVersion,configInfo:a.re}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=C.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=R("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=il();0<c.length&&(b.request={internalExperimentFlags:c});c=a.sd;if(("WEB"===c||"MWEB"===c||1===c||2===c)&&b){var d;b.client.mainAppWebInfo=null!=(d=b.client.mainAppWebInfo)?
d:{};b.client.mainAppWebInfo.webDisplayMode=Tl()}(d=E("yt.embedded_player.embed_url"))&&b&&(b.thirdParty={embedUrl:d});var e;if(S("web_log_memory_total_kbytes")&&(null==(e=C.navigator)?0:e.deviceMemory)){var f;e=null==(f=C.navigator)?void 0:f.deviceMemory;b&&(b.client.memoryTotalKbytes=""+1E6*e)}a.appInstallData&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);(a=im())&&b&&(b.client.connectionType=a);S("web_log_effective_connection_type")&&(a=jm())&&
b&&(b.client.effectiveConnectionType=a);S("start_client_gcf")&&(e=So())&&(a=e.coldConfigData,f=e.coldHashData,e=e.hotHashData,a&&f&&e&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.coldConfigData=a,b.client.configInfo.coldHashData=f,b.client.configInfo.hotHashData=e));R("DELEGATED_SESSION_ID")&&!S("pageid_as_header_web")&&(b.user={onBehalfOfUser:R("DELEGATED_SESSION_ID")});!S("fill_delegate_context_in_gel_killswitch")&&(a=R("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&
(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=Object;f=a.assign;e=b.client;d={};c=v(Object.entries(al(R("DEVICE",""))));for(var g=c.next();!g.done;g=c.next()){var h=v(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?d.deviceMake=h:"cmodel"===g?d.deviceModel=h:"cbr"===g?d.browserName=h:"cbrver"===g?d.browserVersion=h:"cos"===g?d.osName=h:"cosver"===g?d.osVersion=h:"cplatform"===g&&(d.platform=h)}b.client=f.call(a,e,d);return b}
function Wo(a,b,c){c=void 0===c?{}:c;var d={};R("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":R("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||R("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.authorization||R("AUTHORIZATION");b||(a?b="Bearer "+E("gapi.auth.getToken")().Of:(a=Ql(Pl()),S("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
;function Xo(a,b){this.version=a;this.args=b}
Xo.prototype.serialize=function(){return{version:this.version,args:this.args}};function Yo(a,b){this.topic=a;this.h=b}
Yo.prototype.toString=function(){return this.topic};var Zo=E("ytPubsub2Pubsub2Instance")||new L;L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.Jb;L.prototype.publish=L.prototype.ab;L.prototype.clear=L.prototype.clear;D("ytPubsub2Pubsub2Instance",Zo);var $o=E("ytPubsub2Pubsub2SubscribedKeys")||{};D("ytPubsub2Pubsub2SubscribedKeys",$o);var ap=E("ytPubsub2Pubsub2TopicToKeys")||{};D("ytPubsub2Pubsub2TopicToKeys",ap);var bp=E("ytPubsub2Pubsub2IsAsync")||{};D("ytPubsub2Pubsub2IsAsync",bp);
D("ytPubsub2Pubsub2SkipSubKey",null);function cp(a,b){var c=dp();c&&c.publish.call(c,a.toString(),a,b)}
function ep(a){var b=fp,c=dp();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=E("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if($o[d])try{if(f&&b instanceof Yo&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Ya){var l=new h;h.Ya=l.version}var n=h.Ya}catch(z){}if(!n||k.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{n=Reflect;var r=n.construct;
var t=k.args,p=t.length;if(0<p){var x=Array(p);for(k=0;k<p;k++)x[k]=t[k];var y=x}else y=[];f=r.call(n,h,y)}catch(z){throw z.message="yt.pubsub2.Data.deserialize(): "+z.message,z;}}catch(z){throw z.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+z.message,z;}a.call(window,f)}catch(z){Tk(z)}},bp[b.toString()]?E("yt.scheduler.instance")?pi.oa(g):ml(g,0):g())});
$o[d]=!0;ap[b.toString()]||(ap[b.toString()]=[]);ap[b.toString()].push(d);return d}
function gp(){var a=hp,b=ep(function(c){a.apply(void 0,arguments);ip(b)});
return b}
function ip(a){var b=dp();b&&("number"===typeof a&&(a=[a]),db(a,function(c){b.unsubscribeByKey(c);delete $o[c]}))}
function dp(){return E("ytPubsub2Pubsub2Instance")}
;function jp(a,b,c){c=void 0===c?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&cp("meta_logging_csi_event",{timerName:a,kg:b})}
;var kp=hl("max_body_size_to_compress",5E5),lp=hl("min_body_size_to_compress",500),mp=!0,np=0,op=0,pp=hl("compression_performance_threshold_lr",250),qp=hl("slow_compressions_before_abandon_count",4);
function rp(a,b,c,d){var e=T(),f={startTime:e,ticks:{},infos:{}};if(mp)try{var g=sp(b);if(null==g||!(g>kp||g<lp)){var h=nk(ki(b)),k=T();f.ticks.gelc=k;op++;S("disable_compression_due_to_performance_degredation")&&k-e>=pp&&(np++,S("abandon_compression_after_N_slow_zips")?op===hl("compression_disable_point")&&np>qp&&(mp=!1):mp=!1);tp(f);c.headers||(c.headers={});c.headers["Content-Encoding"]="gzip";c.postBody=h;c.postParams=void 0}d(a,c)}catch(l){Uk(l),d(a,c)}else d(a,c)}
function up(a){var b=void 0===b?!1:b;var c=void 0===c?!1:c;var d=T(),e={startTime:d,ticks:{},infos:{}},f=b?E("yt.logging.gzipForFetch",!1):!0;if(mp&&f){if(!a.body)return a;try{var g=c?a.body:"string"===typeof a.body?a.body:JSON.stringify(a.body);f=g;if(!c&&"string"===typeof g){var h=sp(g);if(null!=h&&(h>kp||h<lp))return a;f=nk(ki(g),b?{level:1}:void 0);var k=T();e.ticks.gelc=k;if(b){op++;if((S("disable_compression_due_to_performance_degredation")||S("disable_compression_due_to_performance_degradation_lr"))&&
k-d>=pp)if(np++,S("abandon_compression_after_N_slow_zips")||S("abandon_compression_after_N_slow_zips_lr")){b=np/op;var l=qp/hl("compression_disable_point");0<op&&0===op%hl("compression_disable_point")&&b>=l&&(mp=!1)}else mp=!1;tp(e)}}a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=f;return a}catch(n){return Uk(n),a}}else return a}
function sp(a){try{return(new Blob(a.split(""))).size}catch(b){return Uk(b),null}}
function tp(a){S("gel_compression_csi_killswitch")||!S("log_gel_compression_latency")&&!S("log_gel_compression_latency_lr")||jp("gel_compression",a,{sampleRate:.1})}
;function vp(a){a=Object.assign({},a);delete a.Authorization;var b=xg();if(b){var c=new vi;c.update(R("INNERTUBE_API_KEY"));c.update(b);a.hash=Fe(c.digest(),3)}return a}
;var wp;function xp(){wp||(wp=new Vm("yt.innertube"));return wp}
function yp(a,b,c,d){if(d)return null;d=xp().get("nextId",!0)||1;var e=xp().get("requests",!0)||{};e[d]={method:a,request:b,authState:vp(c),requestTime:Math.round(T())};xp().set("nextId",d+1,86400,!0);xp().set("requests",e,86400,!0);return d}
function zp(a){var b=xp().get("requests",!0)||{};delete b[a];xp().set("requests",b,86400,!0)}
function Ap(a){var b=xp().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(T())-d.requestTime)){var e=d.authState,f=vp(Wo(!1));qb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(T())),Bp(a,d.method,e,{}));delete b[c]}}xp().set("requests",b,86400,!0)}}
;function Cp(a){this.Xb=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.xb=function(){};
this.now=Date.now;this.Pb=!1;var b;this.Kd=null!=(b=a.Kd)?b:100;var c;this.Ed=null!=(c=a.Ed)?c:1;var d;this.Cd=null!=(d=a.Cd)?d:2592E6;var e;this.Ad=null!=(e=a.Ad)?e:12E4;var f;this.Dd=null!=(f=a.Dd)?f:5E3;var g;this.T=null!=(g=a.T)?g:void 0;this.dc=!!a.dc;var h;this.ac=null!=(h=a.ac)?h:.1;var k;this.nc=null!=(k=a.nc)?k:10;a.handleError&&(this.handleError=a.handleError);a.xb&&(this.xb=a.xb);a.Pb&&(this.Pb=a.Pb);a.Xb&&(this.Xb=a.Xb);this.U=a.U;this.Ea=a.Ea;this.ba=a.ba;this.aa=a.aa;this.Ra=a.Ra;this.Qc=
a.Qc;this.Pc=a.Pc;Dp(this)&&(!this.U||this.U("networkless_logging"))&&Ep(this)}
function Ep(a){Dp(a)&&!a.Pb&&(a.h=!0,a.dc&&Math.random()<=a.ac&&a.ba.Zd(a.T),Fp(a),a.aa.wa()&&a.Vb(),a.aa.listen(a.Qc,a.Vb.bind(a)),a.aa.listen(a.Pc,a.gd.bind(a)))}
m=Cp.prototype;m.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(Dp(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.ba.set(d,this.T).then(function(e){d.id=e;c.aa.wa()&&Gp(c,d)}).catch(function(e){Gp(c,d);
Hp(c,e)})}else this.Ra(a,b)};
m.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(Dp(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.U&&this.U("nwl_skip_retry")&&(e.skipRetry=c);if(this.aa.wa()||this.U&&this.U("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return A(function(k){if(1==k.h)return k.yield(d.ba.set(e,d.T).catch(function(l){Hp(d,l)}),2);
f(g,h);k.h=0})}}this.Ra(a,b,e.skipRetry)}else this.ba.set(e,this.T).catch(function(g){d.Ra(a,b,e.skipRetry);
Hp(d,g)})}else this.Ra(a,b,this.U&&this.U("nwl_skip_retry")&&c)};
m.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(Dp(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.ba.tb(d.id,c.T):e=!0;c.aa.ib&&c.U&&c.U("vss_network_hint")&&c.aa.ib(!0);f(g,h)};
this.Ra(d.url,d.options);this.ba.set(d,this.T).then(function(g){d.id=g;e&&c.ba.tb(d.id,c.T)}).catch(function(g){Hp(c,g)})}else this.Ra(a,b)};
m.Vb=function(){var a=this;if(!Dp(this))throw Error("IndexedDB is not supported: throttleSend");this.i||(this.i=this.Ea.oa(function(){var b;return A(function(c){if(1==c.h)return c.yield(a.ba.pd("NEW",a.T),2);if(3!=c.h)return b=c.i,b?c.yield(Gp(a,b),3):(a.gd(),c.return());a.i&&(a.i=0,a.Vb());c.h=0})},this.Kd))};
m.gd=function(){this.Ea.qa(this.i);this.i=0};
function Gp(a,b){var c;return A(function(d){switch(d.h){case 1:if(!Dp(a))throw Error("IndexedDB is not supported: immediateSend");if(void 0===b.id){d.v(2);break}return d.yield(a.ba.ze(b.id,a.T),3);case 3:(c=d.i)||a.xb(Error("The request cannot be found in the database."));case 2:if(Ip(a,b,a.Cd)){d.v(4);break}a.xb(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){d.v(5);break}return d.yield(a.ba.tb(b.id,a.T),5);case 5:return d.return();case 4:b.skipRetry||(b=Jp(a,
b));if(!b){d.v(0);break}if(!b.skipRetry||void 0===b.id){d.v(8);break}return d.yield(a.ba.tb(b.id,a.T),8);case 8:a.Ra(b.url,b.options,!!b.skipRetry),d.h=0}})}
function Jp(a,b){if(!Dp(a))throw Error("IndexedDB is not supported: updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,l;return A(function(n){switch(n.h){case 1:g=Kp(f);(h=Lp(f))&&a.U&&a.U("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.U&&a.U("nwl_consider_error_code")&&g||a.U&&!a.U("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.nc)){n.v(2);break}if(!a.aa.qc){n.v(3);break}return n.yield(a.aa.qc(),3);case 3:if(a.aa.wa()){n.v(2);break}c(e,f);if(!a.U||!a.U("nwl_consider_error_code")||void 0===(null==(k=b)?void 0:k.id)){n.v(6);
break}return n.yield(a.ba.Tc(b.id,a.T,!1),6);case 6:return n.return();case 2:if(a.U&&a.U("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.nc)return n.return();a.potentialEsfErrorCounter++;if(void 0===(null==(l=b)?void 0:l.id)){n.v(8);break}return b.sendCount<a.Ed?n.yield(a.ba.Tc(b.id,a.T,!0,h?!1:void 0),12):n.yield(a.ba.tb(b.id,a.T),8);case 12:a.Ea.oa(function(){a.aa.wa()&&a.Vb()},a.Dd);
case 8:c(e,f),n.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return A(function(h){if(1==h.h)return void 0===(null==(g=b)?void 0:g.id)?h.v(2):h.yield(a.ba.tb(b.id,a.T),2);a.aa.ib&&a.U&&a.U("vss_network_hint")&&a.aa.ib(!0);d(e,f);h.h=0})};
return b}
function Ip(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function Fp(a){if(!Dp(a))throw Error("IndexedDB is not supported: retryQueuedRequests");a.ba.pd("QUEUED",a.T).then(function(b){b&&!Ip(a,b,a.Ad)?a.Ea.oa(function(){return A(function(c){if(1==c.h)return void 0===b.id?c.v(2):c.yield(a.ba.Tc(b.id,a.T),2);Fp(a);c.h=0})}):a.aa.wa()&&a.Vb()})}
function Hp(a,b){a.Qd&&!a.aa.wa()?a.Qd(b):a.handleError(b)}
function Dp(a){return!!a.T||a.Xb}
function Kp(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
function Lp(a){var b;a=null==a?void 0:null==(b=a.error)?void 0:b.code;return!(400!==a&&415!==a)}
;var Mp;
function Np(){if(Mp)return Mp();var a={};Mp=Fo("LogsDatabaseV2",{Gb:(a.LogsRequestsStore={Lb:2},a),sc:!1,upgrade:function(b,c,d){c(2)&&Ln(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),Sn(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return Mp()}
;function Op(a){return eo(Np(),a)}
function Pp(a,b){var c,d,e,f;return A(function(g){if(1==g.h)return c={startTime:T(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},g.yield(Op(b),2);if(3!=g.h)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:R("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),g.yield(Nn(d,"LogsRequestsStore",e),3);f=g.i;c.ticks.tc=T();Qp(c);return g.return(f)})}
function Rp(a,b){var c,d,e,f,g,h,k;return A(function(l){if(1==l.h)return c={startTime:T(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},l.yield(Op(b),2);if(3!=l.h)return d=l.i,e=R("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,T()],h=IDBKeyRange.bound(f,g),k=void 0,l.yield(Kn(d,["LogsRequestsStore"],{mode:"readwrite",ha:!0},function(n){return Xn(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(r){r.getValue()&&(k=r.getValue(),"NEW"===
a&&(k.status="QUEUED",r.update(k)))})}),3);
c.ticks.tc=T();Qp(c);return l.return(k)})}
function Sp(a,b){var c;return A(function(d){if(1==d.h)return d.yield(Op(b),2);c=d.i;return d.return(Kn(c,["LogsRequestsStore"],{mode:"readwrite",ha:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Gn(f.h.put(g,void 0)).then(function(){return g})})}))})}
function Tp(a,b,c,d){c=void 0===c?!0:c;var e;return A(function(f){if(1==f.h)return f.yield(Op(b),2);e=f.i;return f.return(Kn(e,["LogsRequestsStore"],{mode:"readwrite",ha:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),void 0!==d&&(k.options.compress=d),Gn(h.h.put(k,void 0)).then(function(){return k})):An.resolve(void 0)})}))})}
function Up(a,b){var c;return A(function(d){if(1==d.h)return d.yield(Op(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function Vp(a){var b,c;return A(function(d){if(1==d.h)return d.yield(Op(a),2);b=d.i;c=T()-2592E6;return d.yield(Kn(b,["LogsRequestsStore"],{mode:"readwrite",ha:!0},function(e){return Un(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Wp(){A(function(a){return a.yield(Bo(),0)})}
function Qp(a){S("nwl_csi_killswitch")||jp("networkless_performance",a,{sampleRate:1})}
;var Xp={accountStateChangeSignedIn:23,accountStateChangeSignedOut:24,delayedEventMetricCaptured:11,latencyActionBaselined:6,latencyActionInfo:7,latencyActionTicked:5,offlineTransferStatusChanged:2,offlineImageDownload:335,playbackStartStateChanged:9,systemHealthCaptured:3,mangoOnboardingCompleted:10,mangoPushNotificationReceived:230,mangoUnforkDbMigrationError:121,mangoUnforkDbMigrationSummary:122,mangoUnforkDbMigrationPreunforkDbVersionNumber:133,mangoUnforkDbMigrationPhoneMetadata:134,mangoUnforkDbMigrationPhoneStorage:135,
mangoUnforkDbMigrationStep:142,mangoAsyncApiMigrationEvent:223,mangoDownloadVideoResult:224,mangoHomepageVideoCount:279,mangoHomeV3State:295,mangoImageClientCacheHitEvent:273,sdCardStatusChanged:98,framesDropped:12,thumbnailHovered:13,deviceRetentionInfoCaptured:14,thumbnailLoaded:15,backToAppEvent:318,streamingStatsCaptured:17,offlineVideoShared:19,appCrashed:20,youThere:21,offlineStateSnapshot:22,mdxSessionStarted:25,mdxSessionConnected:26,mdxSessionDisconnected:27,bedrockResourceConsumptionSnapshot:28,
nextGenWatchWatchSwiped:29,kidsAccountsSnapshot:30,zeroStepChannelCreated:31,tvhtml5SearchCompleted:32,offlineSharePairing:34,offlineShareUnlock:35,mdxRouteDistributionSnapshot:36,bedrockRepetitiveActionTimed:37,unpluggedDegradationInfo:229,uploadMp4HeaderMoved:38,uploadVideoTranscoded:39,uploadProcessorStarted:46,uploadProcessorEnded:47,uploadProcessorReady:94,uploadProcessorRequirementPending:95,uploadProcessorInterrupted:96,uploadFrontendEvent:241,assetPackDownloadStarted:41,assetPackDownloaded:42,
assetPackApplied:43,assetPackDeleted:44,appInstallAttributionEvent:459,playbackSessionStopped:45,adBlockerMessagingShown:48,distributionChannelCaptured:49,dataPlanCpidRequested:51,detailedNetworkTypeCaptured:52,sendStateUpdated:53,receiveStateUpdated:54,sendDebugStateUpdated:55,receiveDebugStateUpdated:56,kidsErrored:57,mdxMsnSessionStatsFinished:58,appSettingsCaptured:59,mdxWebSocketServerHttpError:60,mdxWebSocketServer:61,startupCrashesDetected:62,coldStartInfo:435,offlinePlaybackStarted:63,liveChatMessageSent:225,
liveChatUserPresent:434,liveChatBeingModerated:457,liveCreationCameraUpdated:64,liveCreationEncodingCaptured:65,liveCreationError:66,liveCreationHealthUpdated:67,liveCreationVideoEffectsCaptured:68,liveCreationStageOccured:75,liveCreationBroadcastScheduled:123,liveCreationArchiveReplacement:149,liveCreationCostreamingConnection:421,liveCreationStreamWebrtcStats:288,mdxSessionRecoveryStarted:69,mdxSessionRecoveryCompleted:70,mdxSessionRecoveryStopped:71,visualElementShown:72,visualElementHidden:73,
visualElementGestured:78,visualElementStateChanged:208,screenCreated:156,playbackAssociated:202,visualElementAttached:215,playbackContextEvent:214,cloudCastingPlaybackStarted:74,webPlayerApiCalled:76,tvhtml5AccountDialogOpened:79,foregroundHeartbeat:80,foregroundHeartbeatScreenAssociated:111,kidsOfflineSnapshot:81,mdxEncryptionSessionStatsFinished:82,playerRequestCompleted:83,liteSchedulerStatistics:84,mdxSignIn:85,spacecastMetadataLookupRequested:86,spacecastBatchLookupRequested:87,spacecastSummaryRequested:88,
spacecastPlayback:89,spacecastDiscovery:90,tvhtml5LaunchUrlComponentChanged:91,mdxBackgroundPlaybackRequestCompleted:92,mdxBrokenAdditionalDataDeviceDetected:93,tvhtml5LocalStorage:97,tvhtml5DeviceStorageStatus:147,autoCaptionsAvailable:99,playbackScrubbingEvent:339,flexyState:100,interfaceOrientationCaptured:101,mainAppBrowseFragmentCache:102,offlineCacheVerificationFailure:103,offlinePlaybackExceptionDigest:217,vrCopresenceStats:104,vrCopresenceSyncStats:130,vrCopresenceCommsStats:137,vrCopresencePartyStats:153,
vrCopresenceEmojiStats:213,vrCopresenceEvent:141,vrCopresenceFlowTransitEvent:160,vrPlaybackEvent:345,kidsAgeGateTracking:105,offlineDelayAllowedTracking:106,mainAppAutoOfflineState:107,videoAsThumbnailDownload:108,videoAsThumbnailPlayback:109,liteShowMore:110,renderingError:118,kidsProfilePinGateTracking:119,abrTrajectory:124,scrollEvent:125,streamzIncremented:126,kidsProfileSwitcherTracking:127,kidsProfileCreationTracking:129,buyFlowStarted:136,mbsConnectionInitiated:138,mbsPlaybackInitiated:139,
mbsLoadChildren:140,liteProfileFetcher:144,mdxRemoteTransaction:146,reelPlaybackError:148,reachabilityDetectionEvent:150,mobilePlaybackEvent:151,courtsidePlayerStateChanged:152,musicPersistentCacheChecked:154,musicPersistentCacheCleared:155,playbackInterrupted:157,playbackInterruptionResolved:158,fixFopFlow:159,anrDetection:161,backstagePostCreationFlowEnded:162,clientError:163,gamingAccountLinkStatusChanged:164,liteHousewarming:165,buyFlowEvent:167,kidsParentalGateTracking:168,kidsSignedOutSettingsStatus:437,
kidsSignedOutPauseHistoryFixStatus:438,tvhtml5WatchdogViolation:444,ypcUpgradeFlow:169,yongleStudy:170,ypcUpdateFlowStarted:171,ypcUpdateFlowCancelled:172,ypcUpdateFlowSucceeded:173,ypcUpdateFlowFailed:174,liteGrowthkitPromo:175,paymentFlowStarted:341,transactionFlowShowPaymentDialog:405,transactionFlowStarted:176,transactionFlowSecondaryDeviceStarted:222,transactionFlowSecondaryDeviceSignedOutStarted:383,transactionFlowCancelled:177,transactionFlowPaymentCallBackReceived:387,transactionFlowPaymentSubmitted:460,
transactionFlowPaymentSucceeded:329,transactionFlowSucceeded:178,transactionFlowFailed:179,transactionFlowPlayBillingConnectionStartEvent:428,transactionFlowSecondaryDeviceSuccess:458,transactionFlowErrorEvent:411,liteVideoQualityChanged:180,watchBreakEnablementSettingEvent:181,watchBreakFrequencySettingEvent:182,videoEffectsCameraPerformanceMetrics:183,adNotify:184,startupTelemetry:185,playbackOfflineFallbackUsed:186,outOfMemory:187,ypcPauseFlowStarted:188,ypcPauseFlowCancelled:189,ypcPauseFlowSucceeded:190,
ypcPauseFlowFailed:191,uploadFileSelected:192,ypcResumeFlowStarted:193,ypcResumeFlowCancelled:194,ypcResumeFlowSucceeded:195,ypcResumeFlowFailed:196,adsClientStateChange:197,ypcCancelFlowStarted:198,ypcCancelFlowCancelled:199,ypcCancelFlowSucceeded:200,ypcCancelFlowFailed:201,ypcCancelFlowGoToPaymentProcessor:402,ypcDeactivateFlowStarted:320,ypcRedeemFlowStarted:203,ypcRedeemFlowCancelled:204,ypcRedeemFlowSucceeded:205,ypcRedeemFlowFailed:206,ypcFamilyCreateFlowStarted:258,ypcFamilyCreateFlowCancelled:259,
ypcFamilyCreateFlowSucceeded:260,ypcFamilyCreateFlowFailed:261,ypcFamilyManageFlowStarted:262,ypcFamilyManageFlowCancelled:263,ypcFamilyManageFlowSucceeded:264,ypcFamilyManageFlowFailed:265,restoreContextEvent:207,embedsAdEvent:327,autoplayTriggered:209,clientDataErrorEvent:210,experimentalVssValidation:211,tvhtml5TriggeredEvent:212,tvhtml5FrameworksFieldTrialResult:216,tvhtml5FrameworksFieldTrialStart:220,musicOfflinePreferences:218,watchTimeSegment:219,appWidthLayoutError:221,accountRegistryChange:226,
userMentionAutoCompleteBoxEvent:227,downloadRecommendationEnablementSettingEvent:228,musicPlaybackContentModeChangeEvent:231,offlineDbOpenCompleted:232,kidsFlowEvent:233,kidsFlowCorpusSelectedEvent:234,videoEffectsEvent:235,unpluggedOpsEogAnalyticsEvent:236,playbackAudioRouteEvent:237,interactionLoggingDebugModeError:238,offlineYtbRefreshed:239,kidsFlowError:240,musicAutoplayOnLaunchAttempted:242,deviceContextActivityEvent:243,deviceContextEvent:244,templateResolutionException:245,musicSideloadedPlaylistServiceCalled:246,
embedsStorageAccessNotChecked:247,embedsHasStorageAccessResult:248,embedsItpPlayedOnReload:249,embedsRequestStorageAccessResult:250,embedsShouldRequestStorageAccessResult:251,embedsRequestStorageAccessState:256,embedsRequestStorageAccessFailedState:257,embedsItpWatchLaterResult:266,searchSuggestDecodingPayloadFailure:252,siriShortcutActivated:253,tvhtml5KeyboardPerformance:254,latencyActionSpan:255,elementsLog:267,ytbFileOpened:268,tfliteModelError:269,tvhtml5ApiTest:270,yongleUsbSetup:271,touStrikeInterstitialEvent:272,
liteStreamToSave:274,appBundleClientEvent:275,ytbFileCreationFailed:276,adNotifyFailure:278,ytbTransferFailed:280,blockingRequestFailed:281,liteAccountSelector:282,liteAccountUiCallbacks:283,dummyPayload:284,browseResponseValidationEvent:285,entitiesError:286,musicIosBackgroundFetch:287,mdxNotificationEvent:289,layersValidationError:290,musicPwaInstalled:291,liteAccountCleanup:292,html5PlayerHealthEvent:293,watchRestoreAttempt:294,liteAccountSignIn:296,notaireEvent:298,kidsVoiceSearchEvent:299,adNotifyFilled:300,
delayedEventDropped:301,analyticsSearchEvent:302,systemDarkThemeOptOutEvent:303,flowEvent:304,networkConnectivityBaselineEvent:305,ytbFileImported:306,downloadStreamUrlExpired:307,directSignInEvent:308,lyricImpressionEvent:309,accessibilityStateEvent:310,tokenRefreshEvent:311,genericAttestationExecution:312,tvhtml5VideoSeek:313,unpluggedAutoPause:314,scrubbingEvent:315,bedtimeReminderEvent:317,tvhtml5UnexpectedRestart:319,tvhtml5StabilityTraceEvent:478,tvhtml5OperationHealth:467,tvhtml5WatchKeyEvent:321,
voiceLanguageChanged:322,tvhtml5LiveChatStatus:323,parentToolsCorpusSelectedEvent:324,offerAdsEnrollmentInitiated:325,networkQualityIntervalEvent:326,deviceStartupMetrics:328,heartbeatActionPlayerTransitioned:330,tvhtml5Lifecycle:331,heartbeatActionPlayerHalted:332,adaptiveInlineMutedSettingEvent:333,mainAppLibraryLoadingState:334,thirdPartyLogMonitoringEvent:336,appShellAssetLoadReport:337,tvhtml5AndroidAttestation:338,tvhtml5StartupSoundEvent:340,iosBackgroundRefreshTask:342,iosBackgroundProcessingTask:343,
sliEventBatch:344,postImpressionEvent:346,musicSideloadedPlaylistExport:347,idbUnexpectedlyClosed:348,voiceSearchEvent:349,mdxSessionCastEvent:350,idbQuotaExceeded:351,idbTransactionEnded:352,idbTransactionAborted:353,tvhtml5KeyboardLogging:354,idbIsSupportedCompleted:355,creatorStudioMobileEvent:356,idbDataCorrupted:357,parentToolsAppChosenEvent:358,webViewBottomSheetResized:359,activeStateControllerScrollPerformanceSummary:360,navigatorValidation:361,mdxSessionHeartbeat:362,clientHintsPolyfillDiagnostics:363,
clientHintsPolyfillEvent:364,proofOfOriginTokenError:365,kidsAddedAccountSummary:366,musicWearableDevice:367,ypcRefundFlowEvent:368,tvhtml5PlaybackMeasurementEvent:369,tvhtml5WatermarkMeasurementEvent:370,clientExpGcfPropagationEvent:371,mainAppReferrerIntent:372,leaderLockEnded:373,leaderLockAcquired:374,googleHatsEvent:375,persistentLensLaunchEvent:376,parentToolsChildWelcomeChosenEvent:378,browseThumbnailPreloadEvent:379,finalPayload:380,mdxDialAdditionalDataUpdateEvent:381,webOrchestrationTaskLifecycleRecord:382,
startupSignalEvent:384,accountError:385,gmsDeviceCheckEvent:386,accountSelectorEvent:388,accountUiCallbacks:389,mdxDialAdditionalDataProbeEvent:390,downloadsSearchIcingApiStats:391,downloadsSearchIndexUpdatedEvent:397,downloadsSearchIndexSnapshot:398,dataPushClientEvent:392,kidsCategorySelectedEvent:393,mdxDeviceManagementSnapshotEvent:394,prefetchRequested:395,prefetchableCommandExecuted:396,gelDebuggingEvent:399,webLinkTtsPlayEnd:400,clipViewInvalid:401,persistentStorageStateChecked:403,cacheWipeoutEvent:404,
playerEvent:410,sfvEffectPipelineStartedEvent:412,sfvEffectPipelinePausedEvent:429,sfvEffectPipelineEndedEvent:413,sfvEffectChosenEvent:414,sfvEffectLoadedEvent:415,sfvEffectUserInteractionEvent:465,sfvEffectFirstFrameProcessedLatencyEvent:416,sfvEffectAggregatedFramesProcessedLatencyEvent:417,sfvEffectAggregatedFramesDroppedEvent:418,sfvEffectPipelineErrorEvent:430,sfvEffectGraphFrozenEvent:419,sfvEffectGlThreadBlockedEvent:420,mdeVideoChangedEvent:442,mdePlayerPerformanceMetrics:472,genericClientExperimentEvent:423,
homePreloadTaskScheduled:424,homePreloadTaskExecuted:425,homePreloadCacheHit:426,polymerPropertyChangedInObserver:427,applicationStarted:431,networkCronetRttBatch:432,networkCronetRttSummary:433,repeatChapterLoopEvent:436,seekCancellationEvent:462,lockModeTimeoutEvent:483,offlineTransferStarted:4,musicOfflineMixtapePreferencesChanged:16,mangoDailyNewVideosNotificationAttempt:40,mangoDailyNewVideosNotificationError:77,dtwsPlaybackStarted:112,dtwsTileFetchStarted:113,dtwsTileFetchCompleted:114,dtwsTileFetchStatusChanged:145,
dtwsKeyframeDecoderBufferSent:115,dtwsTileUnderflowedOnNonkeyframe:116,dtwsBackfillFetchStatusChanged:143,dtwsBackfillUnderflowed:117,dtwsAdaptiveLevelChanged:128,blockingVisitorIdTimeout:277,liteSocial:18,mobileJsInvocation:297,biscottiBasedDetection:439,coWatchStateChange:440,embedsVideoDataDidChange:441,shortsFirst:443,cruiseControlEvent:445,qoeClientLoggingContext:446,atvRecommendationJobExecuted:447,tvhtml5UserFeedback:448,producerProjectCreated:449,producerProjectOpened:450,producerProjectDeleted:451,
producerProjectElementAdded:453,producerProjectElementRemoved:454,tvhtml5ShowClockEvent:455,deviceCapabilityCheckMetrics:456,youtubeClearcutEvent:461,offlineBrowseFallbackEvent:463,getCtvTokenEvent:464,startupDroppedFramesSummary:466,screenshotEvent:468,miniAppPlayEvent:469,elementsDebugCounters:470,fontLoadEvent:471,webKillswitchReceived:473,webKillswitchExecuted:474,cameraOpenEvent:475,manualSmoothnessMeasurement:476,tvhtml5AppQualityEvent:477,polymerPropertyAccessEvent:479,miniAppSdkUsage:480,
cobaltTelemetryEvent:481,crossDevicePlayback:482,channelCreatedWithObakeImage:484,channelEditedWithObakeImage:485};var Yp={},Zp=Fo("ServiceWorkerLogsDatabase",{Gb:(Yp.SWHealthLog={Lb:1},Yp),sc:!0,upgrade:function(a,b){b(1)&&Sn(Ln(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function $p(a){return eo(Zp(),a)}
function aq(a){var b,c;A(function(d){if(1==d.h)return d.yield($p(a),2);b=d.i;c=T()-2592E6;return d.yield(Kn(b,["SWHealthLog"],{mode:"readwrite",ha:!0},function(e){return Un(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function bq(a){var b;return A(function(c){if(1==c.h)return c.yield($p(a),2);b=c.i;return c.yield(b.clear("SWHealthLog"),0)})}
;var cq={},dq=0;function eq(a){var b=new Image,c=""+dq++;cq[c]=b;b.onload=b.onerror=function(){delete cq[c]};
b.src=a}
;function fq(){this.h=new Map;this.i=!1}
function gq(){if(!fq.h){var a=E("yt.networkRequestMonitor.instance")||new fq;D("yt.networkRequestMonitor.instance",a);fq.h=a}return fq.h}
fq.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
fq.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:!1===a&&this.i?!0:null};
fq.prototype.removeParams=function(a){return a.split("?")[0]};
fq.prototype.removeParams=fq.prototype.removeParams;fq.prototype.isEndpointCFR=fq.prototype.isEndpointCFR;fq.prototype.requestComplete=fq.prototype.requestComplete;fq.getInstance=gq;var hq;function iq(){hq||(hq=new Vm("yt.offline"));return hq}
function jq(a){if(S("offline_error_handling")){var b=iq().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);iq().set("errors",b,2592E3,!0)}}
;function kq(){ud.call(this);var a=this;this.j=!1;this.i=oi();this.i.listen("networkstatus-online",function(){if(a.j&&S("offline_error_handling")){var b=iq().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new km(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;Tk(d)}iq().set("errors",{},2592E3,!0)}}})}
w(kq,ud);function lq(){if(!kq.h){var a=E("yt.networkStatusManager.instance")||new kq;D("yt.networkStatusManager.instance",a);kq.h=a}return kq.h}
m=kq.prototype;m.wa=function(){return this.i.wa()};
m.ib=function(a){this.i.i=a};
m.ne=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
m.de=function(){this.j=!0};
m.listen=function(a,b){return this.i.listen(a,b)};
m.qc=function(a){a=mi(this.i,a);a.then(function(b){S("use_cfr_monitor")&&gq().requestComplete("generate_204",b)});
return a};
kq.prototype.sendNetworkCheckRequest=kq.prototype.qc;kq.prototype.listen=kq.prototype.listen;kq.prototype.enableErrorFlushing=kq.prototype.de;kq.prototype.getWindowStatus=kq.prototype.ne;kq.prototype.networkStatusHint=kq.prototype.ib;kq.prototype.isNetworkAvailable=kq.prototype.wa;kq.getInstance=lq;function mq(a){a=void 0===a?{}:a;ud.call(this);var b=this;this.i=this.m=0;this.j=lq();var c=E("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.pc?(this.pc=a.pc,c("networkstatus-online",function(){nq(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){nq(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){vd(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){vd(b,"publicytnetworkstatus-offline")})))}
w(mq,ud);mq.prototype.wa=function(){var a=E("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
mq.prototype.ib=function(a){var b=E("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
mq.prototype.qc=function(a){var b=this,c;return A(function(d){c=E("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return S("skip_network_check_if_cfr")&&gq().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.ib((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.wa())})):c?d.return(c(a)):d.return(!0)})};
function nq(a,b){a.pc?a.i?(pi.qa(a.m),a.m=pi.oa(function(){a.l!==b&&(vd(a,b),a.l=b,a.i=T())},a.pc-(T()-a.i))):(vd(a,b),a.l=b,a.i=T()):vd(a,b)}
;var oq;function pq(){var a=Cp.call;oq||(oq=new mq({Zf:!0,Sf:!0}));a.call(Cp,this,{ba:{Zd:Vp,tb:Up,pd:Rp,ze:Sp,Tc:Tp,set:Pp},aa:oq,handleError:function(b,c,d){var e,f=null==d?void 0:null==(e=d.error)?void 0:e.code;if(400===f||415===f){var g;Uk(new km(b.message,c,null==d?void 0:null==(g=d.error)?void 0:g.code),void 0,void 0,void 0,!0)}else Tk(b)},
xb:Uk,Ra:qq,now:T,Qd:jq,Ea:Um(),Qc:"publicytnetworkstatus-online",Pc:"publicytnetworkstatus-offline",dc:!0,ac:.1,nc:hl("potential_esf_error_limit",10),U:S,Pb:!(lm()&&rq())});this.j=new Dh;S("networkless_immediately_drop_all_requests")&&Wp();Co("LogsDatabaseV2")}
w(pq,Cp);function sq(){var a=E("yt.networklessRequestController.instance");a||(a=new pq,D("yt.networklessRequestController.instance",a),S("networkless_logging")&&ro().then(function(b){a.T=b;Ep(a);a.j.resolve();a.dc&&Math.random()<=a.ac&&a.T&&aq(a.T);S("networkless_immediately_drop_sw_health_store")&&tq(a)}));
return a}
pq.prototype.writeThenSend=function(a,b){b||(b={});lm()||(this.h=!1);Cp.prototype.writeThenSend.call(this,a,b)};
pq.prototype.sendThenWrite=function(a,b,c){b||(b={});lm()||(this.h=!1);Cp.prototype.sendThenWrite.call(this,a,b,c)};
pq.prototype.sendAndWrite=function(a,b){b||(b={});lm()||(this.h=!1);Cp.prototype.sendAndWrite.call(this,a,b)};
pq.prototype.awaitInitialization=function(){return this.j.promise};
function tq(a){var b;A(function(c){if(!a.T)throw b=wn("clearSWHealthLogsDb"),b;return c.return(bq(a.T).catch(function(d){a.handleError(d)}))})}
function qq(a,b,c){b=S("web_fp_via_jspb")?Object.assign({},b):b;S("use_cfr_monitor")&&uq(a,b);if(S("use_request_time_ms_header"))b.headers&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(T())));else{var d;if(null==(d=b.postParams)?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(T())}if(c&&0===Object.keys(b).length){var e=void 0===e?"":e;var f=void 0===f?!1:f;var g=void 0===g?!1:g;if(a)if(e)wl(a,void 0,"POST",e);else if(R("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))wl(a,void 0,"GET",
"",void 0,void 0,f,g);else{b:{try{var h=new $a({url:a});if(h.j&&h.i||h.l){var k=ac(bc(5,a)),l;if(!(l=!k||!k.endsWith("/aclk"))){var n=a.search(oc),r=nc(a,0,"ri",n);if(0>r)var t=null;else{var p=a.indexOf("&",r);if(0>p||p>n)p=n;t=decodeURIComponent(a.slice(r+3,-1!==p?p:0).replace(/\+/g," "))}l="1"!==t}var x=!l;break b}}catch(z){}x=!1}if(x){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var y=!0;break b}}catch(z){}y=!1}c=y?!0:!1}else c=!1;c||eq(a)}}else b.compress?
b.postBody?("string"!==typeof b.postBody&&(b.postBody=JSON.stringify(b.postBody)),rp(a,b.postBody,b,tl)):rp(a,JSON.stringify(b.postParams),b,Bl):tl(a,b)}
function uq(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){gq().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){gq().requestComplete(a,!0);d(e,f)}}
function rq(){return"www.youtube-nocookie.com"!==cc(document.location.toString())}
;var vq=!1,wq=C.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:vq};D("ytNetworklessLoggingInitializationOptions",wq);function xq(){var a;A(function(b){if(1==b.h)return b.yield(ro(),2);a=b.i;if(!a||!lm()&&!S("nwl_init_require_datasync_id_killswitch")||!rq())return b.v(0);vq=!0;wq.isNwlInitialized=vq;return b.yield(sq().awaitInitialization(),0)})}
;function yq(a){var b=this;this.config_=null;a?this.config_=a:To()&&(this.config_=Uo());om(function(){Ap(b)},5E3)}
yq.prototype.isReady=function(){!this.config_&&To()&&(this.config_=Uo());return!!this.config_};
function Bp(a,b,c,d){function e(x){x=void 0===x?!1:x;var y;if(d.retry&&"www.youtube-nocookie.com"!=h&&(x||S("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(y=yp(b,c,l,k)),y)){var z=g.onSuccess,H=g.onFetchSuccess;g.onSuccess=function(M,N){zp(y);z(M,N)};
c.onFetchSuccess=function(M,N){zp(y);H(M,N)}}try{if(x&&d.retry&&!d.vd.bypassNetworkless)g.method="POST",d.vd.writeThenSend?sq().writeThenSend(p,g):sq().sendAndWrite(p,g);
else if(d.compress)if(g.postBody){var I=g.postBody;"string"!==typeof I&&(I=JSON.stringify(g.postBody));rp(p,I,g,tl)}else rp(p,JSON.stringify(g.postParams),g,Bl);else S("web_all_payloads_via_jspb")?tl(p,g):Bl(p,g)}catch(M){if("InvalidAccessError"==M.name)y&&(zp(y),y=0),Uk(Error("An extension is blocking network request."));else throw M;}y&&om(function(){Ap(a)},5E3)}
!R("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Uk(new km("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new km("innertube xhrclient not ready",b,c,d);Tk(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(x,y){if(d.onSuccess)d.onSuccess(y)},
onFetchSuccess:function(x){if(d.onSuccess)d.onSuccess(x)},
onError:function(x,y){if(d.onError)d.onError(y)},
onFetchError:function(x){if(d.onError)d.onError(x)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.ue)&&(h=f);var k=a.config_.xe||!1,l=Wo(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var n="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,r={alt:"json"},t=a.config_.we&&f;t=t&&f.startsWith("Bearer");t||(r.key=a.config_.innertubeApiKey);var p=cl(""+h+n,r||{},!0);(E("ytNetworklessLoggingInitializationOptions")?
wq.isNwlInitialized:vq)?po().then(function(x){e(x)}):e(!1)}
;var zq=0,Aq=Mc?"webkit":Lc?"moz":Jc?"ms":Ic?"o":"";D("ytDomDomGetNextId",E("ytDomDomGetNextId")||function(){return++zq});var Bq={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Cq(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Bq||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function Dq(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
Cq.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Cq.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Cq.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var mb=C.ytEventsEventsListeners||{};D("ytEventsEventsListeners",mb);var Eq=C.ytEventsEventsCounter||{count:0};D("ytEventsEventsCounter",Eq);
function Fq(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return lb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Oa(e[4])&&Oa(d)&&qb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Gq=bb(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Hq(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Fq(a,b,c,d);if(e)return e;e=++Eq.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Cq(h);if(!Ed(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Cq(h);
h.currentTarget=a;return c.call(a,h)};
g=Sk(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Gq()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);mb[e]=[a,b,c,g,d];return e}
function Iq(a){a&&("string"==typeof a&&(a=[a]),db(a,function(b){if(b in mb){var c=mb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Gq()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete mb[b]}}))}
;function Jq(a){this.D=a;this.h=null;this.l=0;this.s=null;this.m=0;this.i=[];for(a=0;4>a;a++)this.i.push(0);this.j=0;this.S=Hq(window,"mousemove",Ua(this.W,this));a=Ua(this.R,this);"function"===typeof a&&(a=Sk(a));this.Y=window.setInterval(a,25)}
Xa(Jq,G);Jq.prototype.W=function(a){void 0===a.h&&Dq(a);var b=a.h;void 0===a.i&&Dq(a);this.h=new Ad(b,a.i)};
Jq.prototype.R=function(){if(this.h){var a=T();if(0!=this.l){var b=this.s,c=this.h,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.l);this.i[this.j]=.5<Math.abs((d-this.m)/this.m)?1:0;for(c=b=0;4>c;c++)b+=this.i[c]||0;3<=b&&this.D();this.m=d}this.l=a;this.s=this.h;this.j=(this.j+1)%4}};
Jq.prototype.M=function(){window.clearInterval(this.Y);Iq(this.S)};var Kq=new Set([174,173,175]),Lq={};
function Mq(a){var b=void 0===a?{}:a;a=void 0===b.He?!1:b.He;b=void 0===b.ee?!0:b.ee;if(null==E("_lact",window)){var c=parseInt(R("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;D("_lact",c,window);D("_fact",c,window);-1==c&&Nq();Hq(document,"keydown",Nq);Hq(document,"keyup",Nq);Hq(document,"mousedown",Nq);Hq(document,"mouseup",Nq);a?Hq(window,"touchmove",function(){Oq("touchmove",200)},{passive:!0}):(Hq(window,"resize",function(){Oq("resize",200)}),b&&Hq(window,"scroll",function(){Oq("scroll",
200)}));
new Jq(function(){Oq("mouse",100)});
Hq(document,"touchstart",Nq,{passive:!0});Hq(document,"touchend",Nq,{passive:!0})}}
function Oq(a,b){Lq[a]||(Lq[a]=!0,pi.oa(function(){Nq();Lq[a]=!1},b))}
function Nq(a){var b;if(null!=(b=E("experiment.flags",window))&&b.enable_lact_reset_by_volume_buttons||!Kq.has(null==a?void 0:a.keyCode))null==E("_lact",window)&&Mq(),a=Date.now(),D("_lact",a,window),-1==E("_fact",window)&&D("_fact",a,window),(a=E("ytglobal.ytUtilActivityCallback_"))&&a()}
function Sq(){var a=E("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var Tq=C.ytPubsubPubsubInstance||new L,Uq=C.ytPubsubPubsubSubscribedKeys||{},Vq=C.ytPubsubPubsubTopicToKeys||{},Wq=C.ytPubsubPubsubIsSynchronous||{};function Xq(a,b){var c=Yq();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){Uq[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{Wq[a]?f():ml(f,0)}catch(g){Tk(g)}},void 0);
Uq[d]=!0;Vq[a]||(Vq[a]=[]);Vq[a].push(d);return d}return 0}
function Zq(a){var b=Yq();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),db(a,function(c){b.unsubscribeByKey(c);delete Uq[c]}))}
function $q(a,b){var c=Yq();c&&c.publish.apply(c,arguments)}
function ar(a){var b=Yq();if(b)if(b.clear(a),a)br(a);else for(var c in Vq)br(c)}
function Yq(){return C.ytPubsubPubsubInstance}
function br(a){Vq[a]&&(a=Vq[a],db(a,function(b){Uq[b]&&delete Uq[b]}),a.length=0)}
L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.Jb;L.prototype.publish=L.prototype.ab;L.prototype.clear=L.prototype.clear;D("ytPubsubPubsubInstance",Tq);D("ytPubsubPubsubTopicToKeys",Vq);D("ytPubsubPubsubIsSynchronous",Wq);D("ytPubsubPubsubSubscribedKeys",Uq);var cr=Symbol("injectionDeps");function dr(a){this.name=a}
dr.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function er(a){this.key=a}
function fr(){this.h=new Map;this.i=new Map}
fr.prototype.resolve=function(a){return a instanceof er?gr(this,a.key,[],!0):gr(this,a,[])};
function gr(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.i.has(b))return a.i.get(b);if(!a.h.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.h.get(b);c.push(b);if(void 0!==d.Nd)var e=d.Nd;else if(d.kf)e=d[cr]?hr(a,d[cr],c):[],e=d.kf.apply(d,ja(e));else if(d.Md){e=d.Md;var f=e[cr]?hr(a,e[cr],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ja(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.ig||a.i.set(b,e);return e}
function hr(a,b,c){return b?b.map(function(d){return d instanceof er?gr(a,d.key,c,!0):gr(a,d,c)}):[]}
;var ir;function jr(){ir||(ir=new fr);return ir}
;var kr=window;function lr(){var a,b;return"h5vcc"in kr&&(null==(a=kr.h5vcc.traceEvent)?0:a.traceBegin)&&(null==(b=kr.h5vcc.traceEvent)?0:b.traceEnd)?1:"performance"in kr&&kr.performance.mark&&kr.performance.measure?2:0}
function mr(a){switch(lr()){case 1:kr.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:kr.performance.mark(a+"-start");break;case 0:break;default:Ph()}}
function nr(a){switch(lr()){case 1:kr.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:var b=a+"-start",c=a+"-end";kr.performance.mark(c);kr.performance.measure(a,b,c);break;case 0:break;default:Ph()}}
;var or=S("web_enable_lifecycle_monitoring")&&0!==lr(),pr=S("web_enable_lifecycle_monitoring");function qr(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?Um():d;this.j=c;this.scheduler=d;this.i=new Dh;this.h=a;for(a={fb:0};a.fb<this.h.length;a={Sb:a.Sb,fb:a.fb},a.fb++)a.Sb=this.h[a.fb],c=function(e){return function(){e.Sb.Kc();b.h[e.fb].oc=!0;b.h.every(function(f){return!0===f.oc})&&b.i.resolve()}}(a),d=this.getPriority(a.Sb),d=this.scheduler.bb(c,d),this.h[a.fb]=Object.assign({},a.Sb,{Kc:c,
jobId:d})}
function rr(a){var b=Array.from(a.h.keys()).sort(function(d,e){return a.getPriority(a.h[e])-a.getPriority(a.h[d])});
b=v(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],void 0===c.jobId||c.oc||(a.scheduler.qa(c.jobId),a.scheduler.bb(c.Kc,10))}
qr.prototype.cancel=function(){for(var a=v(this.h),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.jobId||b.oc||this.scheduler.qa(b.jobId),b.oc=!0;this.i.resolve()};
qr.prototype.getPriority=function(a){var b;return null!=(b=a.priority)?b:this.j};function sr(a){this.state=a;this.plugins=[];this.l=void 0;this.s={};or&&mr(this.state)}
m=sr.prototype;m.install=function(a){this.plugins.push(a);return this};
m.uninstall=function(){var a=this;B.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);-1<b&&a.plugins.splice(b,1)})};
m.transition=function(a,b){var c=this;or&&nr(this.state);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.to===a}):f.from===c.state&&f.to===a});
if(d){this.j&&(rr(this.j),this.j=void 0);tr(this,a,b);this.state=a;or&&mr(this.state);d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(ur(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function ur(a,b){var c=b.filter(function(e){return 10===vr(a,e)}),d=b.filter(function(e){return 10!==vr(a,e)});
return a.s.hg?function(){var e=B.apply(0,arguments);return A(function(f){if(1==f.h)return f.yield(a.Oe.apply(a,[c].concat(ja(e))),2);a.Hd.apply(a,[d].concat(ja(e)));f.h=0})}:function(){var e=B.apply(0,arguments);
a.Pe.apply(a,[c].concat(ja(e)));a.Hd.apply(a,[d].concat(ja(e)))}}
m.Pe=function(a){for(var b=B.apply(1,arguments),c=Um(),d=v(a),e=d.next(),f={};!e.done;f={Cb:f.Cb},e=d.next())f.Cb=e.value,c.Kb(function(g){return function(){wr(g.Cb.name);g.Cb.callback.apply(g.Cb,ja(b));xr(g.Cb.name)}}(f))};
m.Oe=function(a){var b=B.apply(1,arguments),c,d,e,f,g;return A(function(h){1==h.h&&(c=Um(),d=v(a),e=d.next(),f={});if(3!=h.h){if(e.done)return h.v(0);f.gb=e.value;f.Mb=void 0;g=function(k){return function(){wr(k.gb.name);var l=k.gb.callback.apply(k.gb,ja(b));"function"===typeof(null==l?void 0:l.then)?k.Mb=l.then(function(){xr(k.gb.name)}):xr(k.gb.name)}}(f);
c.Kb(g);return f.Mb?h.yield(f.Mb,3):h.v(3)}f={gb:f.gb,Mb:f.Mb};e=d.next();return h.v(2)})};
m.Hd=function(a){var b=B.apply(1,arguments),c=this,d=a.map(function(e){return{Kc:function(){wr(e.name);e.callback.apply(e,ja(b));xr(e.name)},
priority:vr(c,e)}});
d.length&&(this.j=new qr(d))};
function vr(a,b){var c,d;return null!=(d=null!=(c=a.l)?c:b.priority)?d:0}
function wr(a){or&&a&&mr(a)}
function xr(a){or&&a&&nr(a)}
function tr(a,b,c){pr&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
da.Object.defineProperties(sr.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function yr(a){sr.call(this,void 0===a?"none":a);this.h=null;this.l=10;this.transitions=[{from:"none",to:"application_navigating",action:this.i},{from:"application_navigating",to:"none",action:this.m},{from:"application_navigating",to:"application_navigating",action:function(){}},
{from:"none",to:"none",action:function(){}}]}
var zr;w(yr,sr);yr.prototype.i=function(a,b){var c=this;this.h=om(function(){"application_navigating"===c.currentState&&c.transition("none")},5E3);
a(null==b?void 0:b.event)};
yr.prototype.m=function(a,b){this.h&&(pi.qa(this.h),this.h=null);a(null==b?void 0:b.event)};
function Ar(){zr||(zr=new yr);return zr}
;function Br(){this.store={};this.h={}}
Br.prototype.storePayload=function(a,b){a=Cr(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);return a};
Br.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=Dr(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,ja(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,ja(this.store[b[d]].splice(0,a.sizeLimit))));(null==a?0:a.sizeLimit)&&c.length<(null==a?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,ja(this.smartExtractMatchingEntries(a))));return c};
Br.prototype.extractMatchingEntries=function(a){a=Dr(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,ja(this.store[a[c]])),delete this.store[a[c]]);return b};
Br.prototype.getSequenceCount=function(a){a=Dr(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=(null==(d=this.store[a[c]])?void 0:d.length)||0}return b};
function Dr(a,b){var c=Cr(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(1>=d.length&&Cr(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(Er(b.auth,g[0])){var h=b.isJspb;Er(void 0===h?"undefined":h?"true":"false",g[1])&&Er(b.cttAuthInfo,g[2])&&(h=b.tier,h=void 0===h?"undefined":JSON.stringify(h),Er(h,g[3])&&e.push(d[f]))}}return a.h[c]=e}
function Er(a,b){return void 0===a||"undefined"===a?!0:a===b}
Br.prototype.getSequenceCount=Br.prototype.getSequenceCount;Br.prototype.extractMatchingEntries=Br.prototype.extractMatchingEntries;Br.prototype.smartExtractMatchingEntries=Br.prototype.smartExtractMatchingEntries;Br.prototype.storePayload=Br.prototype.storePayload;function Cr(a){return[void 0===a.auth?"undefined":a.auth,void 0===a.isJspb?"undefined":a.isJspb,void 0===a.cttAuthInfo?"undefined":a.cttAuthInfo,void 0===a.tier?"undefined":a.tier].join("/")}
;function U(a,b){if(a)return a[b.name]}
;var Fr=hl("initial_gel_batch_timeout",2E3),Gr=hl("gel_queue_timeout_max_ms",6E4),Hr=Math.pow(2,16)-1,Ir=hl("gel_min_batch_size",5),Jr=void 0;function Kr(){this.l=this.h=this.i=0;this.j=!1}
var Lr=new Kr,Mr=new Kr,Nr=new Kr,Or=new Kr,Pr,Qr=!0,Rr=C.ytLoggingTransportTokensToCttTargetIds_||{};D("ytLoggingTransportTokensToCttTargetIds_",Rr);var Sr={};function Tr(){var a=E("yt.logging.ims");a||(a=new Br,D("yt.logging.ims",a));return a}
function Ur(a,b){if("log_event"===a.endpoint){var c=Vr(a),d=Wr(a.payload)||"";a:{if(S("enable_web_tiered_gel")){var e=Xp[d||""];var f,g,h,k=null==jr().resolve(new er(Oo))?void 0:null==(f=Po())?void 0:null==(g=f.loggingHotConfig)?void 0:null==(h=g.eventLoggingConfig)?void 0:h.payloadPolicies;if(k)for(f=0;f<k.length;f++)if(k[f].payloadNumber===e){e=k[f];break a}}e=void 0}k=200;if(e){if(!1===e.enabled&&!S("web_payload_policy_disabled_killswitch"))return;k=Xr(e.tier);if(400===k){Yr(a,b);return}}Sr[c]=
!0;e={cttAuthInfo:c,isJspb:!1,tier:k};Tr().storePayload(e,a.payload);Zr(b,c,e,"gelDebuggingEvent"===d)}}
function Zr(a,b,c,d){function e(){$r({writeThenSend:!0},S("flush_only_full_queue")?b:void 0,f,c.tier)}
var f=!1;f=void 0===f?!1:f;d=void 0===d?!1:d;a&&(Jr=new a);a=hl("tvhtml5_logging_max_batch_ads_fork")||hl("web_logging_max_batch")||100;var g=T(),h=as(f,c.tier),k=h.l;d&&(h.j=!0);d=0;c&&(d=Tr().getSequenceCount(c));1E3<=d?e():d>=a?Pr||(Pr=bs(function(){e();Pr=void 0},0)):10<=g-k&&(cs(f,c.tier),h.l=g)}
function Yr(a,b){if("log_event"===a.endpoint){var c=Vr(a),d=new Map;d.set(c,[a.payload]);var e=Wr(a.payload)||"";b&&(Jr=new b);return new Rd(function(f,g){Jr&&Jr.isReady()?ds(d,Jr,f,g,{bypassNetworkless:!0},!0,"gelDebuggingEvent"===e):f()})}}
function Vr(a){var b="";if(a.dangerousLogToVisitorSession)b="visitorOnlyApprovedKey";else if(a.cttAuthInfo){b=a.cttAuthInfo;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);Rr[a.cttAuthInfo.token]=c;b=a.cttAuthInfo.token}return b}
function $r(a,b,c,d){a=void 0===a?{}:a;c=void 0===c?!1:c;new Rd(function(e,f){var g=as(c,d),h=g.j;g.j=!1;es(g.i);es(g.h);g.h=0;Jr&&Jr.isReady()?void 0===d&&S("enable_web_tiered_gel")?gs(e,f,a,b,c,300,h):gs(e,f,a,b,c,d,h):(cs(c,d),e())})}
function gs(a,b,c,d,e,f,g){var h=Jr;c=void 0===c?{}:c;e=void 0===e?!1:e;f=void 0===f?200:f;g=void 0===g?!1:g;var k=new Map;var l={isJspb:e,cttAuthInfo:d,tier:f};e={isJspb:e,cttAuthInfo:d};if(void 0!==d)f=S("enable_web_tiered_gel")?Tr().smartExtractMatchingEntries({keys:[l,e],sizeLimit:1E3}):Tr().extractMatchingEntries(e),k.set(d,f);else for(d=v(Object.keys(Sr)),l=d.next();!l.done;l=d.next())l=l.value,e=S("enable_web_tiered_gel")?Tr().smartExtractMatchingEntries({keys:[{isJspb:!1,cttAuthInfo:l,tier:f},
{isJspb:!1,cttAuthInfo:l}],sizeLimit:1E3}):Tr().extractMatchingEntries({isJspb:!1,cttAuthInfo:l}),0<e.length&&k.set(l,e),(S("web_fp_via_jspb_and_json")&&c.writeThenSend||!S("web_fp_via_jspb_and_json"))&&delete Sr[l];ds(k,h,a,b,c,!1,g)}
function cs(a,b){function c(){$r({writeThenSend:!0},void 0,a,b)}
a=void 0===a?!1:a;b=void 0===b?200:b;var d=as(a,b),e=d===Or||d===Nr?5E3:Gr;S("web_gel_timeout_cap")&&!d.h&&(e=bs(function(){c()},e),d.h=e);
es(d.i);e=R("LOGGING_BATCH_TIMEOUT",hl("web_gel_debounce_ms",1E4));S("shorten_initial_gel_batch_timeout")&&Qr&&(e=Fr);e=bs(function(){0<hl("gel_min_batch_size")?Tr().getSequenceCount({cttAuthInfo:void 0,isJspb:a,tier:b})>=Ir&&c():c()},e);
d.i=e}
function ds(a,b,c,d,e,f,g){e=void 0===e?{}:e;var h=Math.round(T()),k=a.size,l=(void 0===g?0:g)&&S("vss_through_gel_video_stats")?"video_stats":"log_event";a=v(a);var n=a.next();for(g={};!n.done;g={jc:g.jc,cb:g.cb,dangerousLogToVisitorSession:g.dangerousLogToVisitorSession,lc:g.lc,kc:g.kc},n=a.next()){var r=v(n.value);n=r.next().value;r=r.next().value;g.cb=sb({context:Vo(b.config_||Uo())});if(!Na(r)&&!S("throw_err_when_logevent_malformed_killswitch")){d();break}g.cb.events=r;(r=Rr[n])&&hs(g.cb,n,r);
delete Rr[n];g.dangerousLogToVisitorSession="visitorOnlyApprovedKey"===n;is(g.cb,h,g.dangerousLogToVisitorSession);S("always_send_and_write")&&(e.writeThenSend=!1);g.lc=function(t){S("start_client_gcf")&&pi.oa(function(){return A(function(p){return p.yield(js(t),0)})});
k--;k||c()};
g.jc=0;g.kc=function(t){return function(){t.jc++;if(e.bypassNetworkless&&1===t.jc)try{Bp(b,l,t.cb,ks({writeThenSend:!0},t.dangerousLogToVisitorSession,t.lc,t.kc,f)),Qr=!1}catch(p){Tk(p),d()}k--;k||c()}}(g);
try{Bp(b,l,g.cb,ks(e,g.dangerousLogToVisitorSession,g.lc,g.kc,f)),Qr=!1}catch(t){Tk(t),d()}}}
function ks(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,vd:a,dangerousLogToVisitorSession:b,Pf:!!e,headers:{},postBodyFormat:"",postBody:"",compress:S("compress_gel")||S("compress_gel_lr")};ls()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(T())));return a}
function is(a,b,c){ls()||(a.requestTimeMs=String(b));S("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=R("EVENT_ID"))&&((c=R("BATCH_CLIENT_COUNTER")||0)||(c=Math.floor(Math.random()*Hr/2)),c++,c>Hr&&(c=1),Ok("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function hs(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function ls(){return S("use_request_time_ms_header")||S("lr_use_request_time_ms_header")}
function bs(a,b){return S("transport_use_scheduler")?S("logging_avoid_blocking_during_navigation")||S("lr_logging_avoid_blocking_during_navigation")?om(function(){if("none"===Ar().currentState)a();else{var c={};Ar().install((c.none={callback:a},c))}},b):om(a,b):ml(a,b)}
function es(a){S("transport_use_scheduler")?pi.qa(a):window.clearTimeout(a)}
function js(a){var b,c,d,e,f,g,h,k,l,n;return A(function(r){return 1==r.h?(d=null==(b=a)?void 0:null==(c=b.responseContext)?void 0:c.globalConfigGroup,e=U(d,rk),g=null==(f=d)?void 0:f.hotHashData,h=U(d,qk),l=null==(k=d)?void 0:k.coldHashData,(n=jr().resolve(new er(Oo)))?g?e?r.yield(Qo(n,g,e),2):r.yield(Qo(n,g),2):r.v(2):r.return()):l?h?r.yield(Ro(n,l,h),0):r.yield(Ro(n,l),0):r.v(0)})}
function as(a,b){b=void 0===b?200:b;return a?300===b?Or:Mr:300===b?Nr:Lr}
function Wr(a){a=Object.keys(a);a=v(a);for(var b=a.next();!b.done;b=a.next())if(b=b.value,Xp[b])return b}
function Xr(a){switch(a){case "DELAYED_EVENT_TIER_UNSPECIFIED":return 0;case "DELAYED_EVENT_TIER_DEFAULT":return 100;case "DELAYED_EVENT_TIER_DISPATCH_TO_EMPTY":return 200;case "DELAYED_EVENT_TIER_FAST":return 300;case "DELAYED_EVENT_TIER_IMMEDIATE":return 400;default:return 200}}
;var ms=C.ytLoggingGelSequenceIdObj_||{};D("ytLoggingGelSequenceIdObj_",ms);
function ns(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||T());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=Sq();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};d.sequenceGroup&&!S("web_gel_sequence_info_killswitch")&&(a=e.context,b=d.sequenceGroup,ms[b]=b in ms?ms[b]+1:0,a.sequence={index:ms[b],groupKey:b},d.endOfSequence&&delete ms[d.sequenceGroup]);(d.sendIsolatedPayload?Yr:Ur)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},
c)}
;function dn(a,b,c){c=void 0===c?{}:c;var d=yq;R("ytLoggingEventsDefaultDisabled",!1)&&yq===yq&&(d=null);S("web_all_payloads_via_jspb")&&!c.timestamp&&(c.lact=Sq(),c.timestamp=T());ns(a,b,d,c)}
;D("ytLoggingGelSequenceIdObj_",C.ytLoggingGelSequenceIdObj_||{});var ps=new Set,qs=0,rs=0,ss=0,ts=[],us=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function cn(a){vs(a)}
function ws(a){vs(a,"WARNING")}
function xs(a){a instanceof Error?vs(a):(a=Oa(a)?JSON.stringify(a):String(a),a=new km(a),a.name="RejectedPromiseError",ws(a))}
function vs(a,b,c,d,e,f,g,h){f=void 0===f?{}:f;f.name=c||R("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||R("INNERTUBE_CONTEXT_CLIENT_VERSION");c=f;b=void 0===b?"ERROR":b;g=void 0===g?!1:g;b=void 0===b?"ERROR":b;g=void 0===g?!1:g;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),S("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+
JSON.stringify(a.args)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),d=d.join("\n"),window.console.log(d,a)),!(5<=qs))){d=ts;var k=Ac(a);e=k.message||"Unknown Error";f=k.name||"UnknownError";var l=k.stack||a.i||"Not available";if(l.startsWith(f+": "+e)){var n=l.split("\n");n.shift();l=n.join("\n")}n=k.lineNumber||"Not available";k=k.fileName||"Not available";var r=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var t=0;t<a.args.length&&!(r=Ll(a.args[t],"params."+t,c,r),
500<=r);t++);else if(a.hasOwnProperty("params")&&a.params){var p=a.params;if("object"===typeof a.params)for(t in p){if(p[t]){var x="params."+t,y=Nl(p[t]);c[x]=y;r+=x.length+y.length;if(500<r)break}}else c.params=Nl(p)}if(d.length)for(t=0;t<d.length&&!(r=Ll(d[t],"params.context."+t,c,r),500<=r);t++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);t={message:e,name:f,lineNumber:n,fileName:k,stack:l,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(t.lineNumber=
t.lineNumber+":"+c);if("IGNORED"===a.level)a=0;else a:{a=Hl();c=v(a.Va);for(d=c.next();!d.done;d=c.next())if(d=d.value,t.message&&t.message.match(d.ag)){a=d.weight;break a}a=v(a.Sa);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.callback(t)){a=c.weight;break a}a=1}t.sampleWeight=a;a=v(Cl);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.mc[t.name])for(e=v(c.mc[t.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=t.message.match(f.regexp)){t.params["params.error.original"]=d[0];e=f.groups;f={};
for(n=0;n<e.length;n++)f[e[n]]=d[n+1],t.params["params.error."+e[n]]=d[n+1];t.message=c.Nc(f);break}t.params||(t.params={});a=Hl();t.params["params.errorServiceSignature"]="msg="+a.Va.length+"&cb="+a.Sa.length;t.params["params.serviceWorker"]="false";C.document&&C.document.querySelectorAll&&(t.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));yb("sample").constructor!==xb&&(t.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(t);
if(0!==t.sampleWeight&&!ps.has(t.message)){if(g&&S("web_enable_error_204"))ys(void 0===b?"ERROR":b,t);else{b=void 0===b?"ERROR":b;"ERROR"===b?(Il.ab("handleError",t),S("record_app_crashed_web")&&0===ss&&1===t.sampleWeight&&(ss++,g={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},S("report_client_error_with_app_crash_ks")||(g.systemHealth={crashData:{clientError:{logMessage:{message:t.message}}}}),dn("appCrashed",g)),rs++):"WARNING"===b&&Il.ab("handleWarning",t);if(S("kevlar_gel_error_routing")){g=b;h=void 0===
h?{}:h;b:{a=v(us);for(c=a.next();!c.done;c=a.next())if(kn(c.value.toLowerCase())){a=!0;break b}a=!1}if(a)h=void 0;else{c={stackTrace:t.stack};t.fileName&&(c.filename=t.fileName);a=t.lineNumber&&t.lineNumber.split?t.lineNumber.split(":"):[];0!==a.length&&(1!==a.length||isNaN(Number(a[0]))?2!==a.length||isNaN(Number(a[0]))||isNaN(Number(a[1]))||(c.lineNumber=Number(a[0]),c.columnNumber=Number(a[1])):c.lineNumber=Number(a[0]));a={level:"ERROR_LEVEL_UNKNOWN",message:t.message,errorClassName:t.name,sampleWeight:t.sampleWeight};
"ERROR"===g?a.level="ERROR_LEVEL_ERROR":"WARNING"===g&&(a.level="ERROR_LEVEL_WARNNING");c={isObfuscated:!0,browserStackInfo:c};h.pageUrl=window.location.href;h.kvPairs=[];R("FEXP_EXPERIMENTS")&&(h.experimentIds=R("FEXP_EXPERIMENTS"));e=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!Pk("web_disable_gel_stp_ecatcher_killswitch")&&e)for(f=v(Object.keys(e)),d=f.next();!d.done;d=f.next())d=d.value,h.kvPairs.push({key:d,value:String(e[d])});if(e=t.params)for(f=v(Object.keys(e)),d=f.next();!d.done;d=f.next())d=
d.value,h.kvPairs.push({key:"client."+d,value:String(e[d])});d=R("SERVER_NAME");e=R("SERVER_VERSION");d&&e&&(h.kvPairs.push({key:"server.name",value:d}),h.kvPairs.push({key:"server.version",value:e}));h={errorMetadata:h,stackTrace:c,logMessage:a}}h&&(dn("clientError",h),("ERROR"===g||S("errors_flush_gel_always_killswitch"))&&$r(void 0,void 0,!1))}S("suppress_error_204_logging")||ys(b,t)}try{ps.add(t.message)}catch(z){}qs++}}}
function ys(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:R("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=v(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=v(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];c=R("SERVER_NAME");b=R("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}tl(R("ECATCHER_REPORT_HOST","")+"/error_204",a)}
;function zs(){this.register=new Map}
function As(a){a=v(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.dg("ABORTED")}
zs.prototype.clear=function(){As(this);this.register.clear()};
var Bs=new zs;var Cs=Date.now().toString();
function Ds(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(Cs)for(a=1,b=0;b<Cs.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^Cs.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var Es,Fs=C.ytLoggingDocDocumentNonce_;Fs||(Fs=Ds(),D("ytLoggingDocDocumentNonce_",Fs));Es=Fs;function Gs(a){this.h=a}
m=Gs.prototype;m.getAsJson=function(){var a={};void 0!==this.h.trackingParams?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,void 0!==this.h.veCounter&&(a.veCounter=this.h.veCounter),void 0!==this.h.elementIndex&&(a.elementIndex=this.h.elementIndex));void 0!==this.h.dataElement&&(a.dataElement=this.h.dataElement.getAsJson());void 0!==this.h.youtubeData&&(a.youtubeData=this.h.youtubeData);this.h.isCounterfactual&&(a.isCounterfactual=!0);return a};
m.getAsJspb=function(){var a=new Ak;void 0!==this.h.trackingParams?J(a,1,kf(this.h.trackingParams,!0)):(void 0!==this.h.veType&&J(a,2,rf(this.h.veType)),void 0!==this.h.veCounter&&J(a,6,rf(this.h.veCounter)),void 0!==this.h.elementIndex&&J(a,3,rf(this.h.elementIndex)),this.h.isCounterfactual&&J(a,5,pf(!0)));if(void 0!==this.h.dataElement){var b=this.h.dataElement.getAsJspb();Wf(a,Ak,7,b)}void 0!==this.h.youtubeData&&Wf(a,tk,8,this.h.jspbYoutubeData);return a};
m.toString=function(){return JSON.stringify(this.getAsJson())};
m.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};
m.getLoggingDirectives=function(){return this.h.loggingDirectives};function Hs(a){return R("client-screen-nonce-store",{})[void 0===a?0:a]}
function Is(a,b){b=void 0===b?0:b;var c=R("client-screen-nonce-store");c||(c={},Ok("client-screen-nonce-store",c));c[b]=a}
function Js(a){a=void 0===a?0:a;return 0===a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function Ks(a){return R(Js(void 0===a?0:a))}
D("yt_logging_screen.getRootVeType",Ks);function Ls(){var a=R("csn-to-ctt-auth-info");a||(a={},Ok("csn-to-ctt-auth-info",a));return a}
function Ms(){return Object.values(R("client-screen-nonce-store",{})).filter(function(a){return void 0!==a})}
function Ns(a){a=Hs(void 0===a?0:a);if(!a&&!R("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
D("yt_logging_screen.getCurrentCsn",Ns);function Os(a,b,c){var d=Ls();(c=Ns(c))&&delete d[c];b&&(d[a]=b)}
function Ps(a){return Ls()[a]}
D("yt_logging_screen.getCttAuthInfo",Ps);D("yt_logging_screen.setCurrentScreen",function(a,b,c,d){c=void 0===c?0:c;if(a!==Hs(c)||b!==R(Js(c)))if(Os(a,d,c),Is(a,c),Ok(Js(c),b),b=function(){setTimeout(function(){a&&dn("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:Es,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()});var Qs=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};D("yt.msgs_",Qs);function Rs(a){Jk(Qs,arguments)}
;function Ss(){var a=rb(Ts),b;return(new Rd(function(c,d){a.onSuccess=function(e){ll(e)?c(new Us(e)):d(new Vs("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Vs("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new Vs("Request timed out","net.timeout",e))};
b=tl("//googleads.g.doubleclick.net/pagead/id",a)})).uc(function(c){c instanceof be&&b.abort();
return Xd(c)})}
function Vs(a,b,c){Za.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
w(Vs,Za);function Us(a){this.xhr=a}
;function Ws(){this.h=0;this.value_=null}
Ws.prototype.then=function(a,b,c){return 1===this.h&&a?(a=a.call(c,this.value_))&&"function"===typeof a.then?a:Xs(a):2===this.h&&b?(a=b.call(c,this.value_))&&"function"===typeof a.then?a:Ys(a):this};
Ws.prototype.getValue=function(){return this.value_};
Ws.prototype.isRejected=function(){return 2==this.h};
Ws.prototype.$goog_Thenable=!0;function Ys(a){var b=new Ws;a=void 0===a?null:a;b.h=2;b.value_=void 0===a?null:a;return b}
function Xs(a){var b=new Ws;a=void 0===a?null:a;b.h=1;b.value_=void 0===a?null:a;return b}
;function Zs(a,b){var c=void 0===c?{}:c;a={method:void 0===b?"POST":b,mode:dl(a)?"same-origin":"cors",credentials:dl(a)?"same-origin":"include"};b={};for(var d=v(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);0<Object.keys(b).length&&(a.headers=b);return a}
;function $s(){return vg()||(Ae||Be)&&kn("applewebkit")&&!kn("version")&&(!kn("safari")||kn("gsa/"))||Oc&&kn("version/")?!0:R("EOM_VISITOR_DATA")?!1:!0}
;function at(a){a:{var b="EMBEDDED_PLAYER_MODE_UNKNOWN";window.location.hostname.includes("youtubeeducation.com")&&(b="EMBEDDED_PLAYER_MODE_PFL");var c=a.raw_embedded_player_response;if(!c&&(a=a.embedded_player_response))try{c=JSON.parse(a)}catch(e){break a}if(c)b:for(var d in yk)if(yk[d]==c.embeddedPlayerMode){b=yk[d];break b}}return"EMBEDDED_PLAYER_MODE_PFL"===b}
;function bt(a){Za.call(this,a.message||a.description||a.name);this.isMissing=a instanceof ct;this.isTimeout=a instanceof Vs&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof be}
w(bt,Za);bt.prototype.name="BiscottiError";function ct(){Za.call(this,"Biscotti ID is missing from server")}
w(ct,Za);ct.prototype.name="BiscottiMissingError";var Ts={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},dt=null;function et(){if(S("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!$s())return Error("User has not consented - not fetching biscotti id.");var a=R("PLAYER_VARS",{});if("1"==pb(a))return Error("Biscotti ID is not available in private embed mode");if(at(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Hk(){var a=et();if(void 0!==a)return Xd(a);dt||(dt=Ss().then(ft).uc(function(b){return gt(2,b)}));
return dt}
function ft(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new ct;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new ct;a=a.id;Ik(a);dt=Xs(a);ht(18E5,2);return a}
function gt(a,b){b=new bt(b);Ik("");dt=Ys(b);0<a&&ht(12E4,a-1);throw b;}
function ht(a,b){ml(function(){Ss().then(ft,function(c){return gt(b,c)}).uc(ab)},a)}
function jt(){try{var a=E("yt.ads.biscotti.getId_");return a?a():Hk()}catch(b){return Xd(b)}}
;function kt(a){if("1"!=pb(R("PLAYER_VARS",{}))){a&&Gk();try{jt().then(function(){},function(){}),ml(kt,18E5)}catch(b){Tk(b)}}}
;function lt(){var a=am(),b=dm(119),c=1<window.devicePixelRatio;if(document.body&&zi(document.body,"exp-invert-logo"))if(c&&!zi(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!zi(d,"inverted-hdpi")){var e=xi(d);yi(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&zi(document.body,"inverted-hdpi")&&Ai();if(b!=c){b="f"+(Math.floor(119/31)+1);d=em(b)||0;d=c?d|67108864:d&-67108865;0===d?delete Yl[b]:(c=d.toString(16),Yl[b]=c.toString());
c=!0;S("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(f in Yl)Yl.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(Yl[f])));var f=d.join("&");Ul(b,f,63072E3,a.i,c)}}
;var mt=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function nt(){var a=void 0===a?window.location.href:a;if(S("kevlar_disable_theme_param"))return null;ac(bc(5,a));try{var b=bl(a).theme;return mt.get(b)||null}catch(c){}return null}
;function ot(){this.h={};if(this.i=Xl()){var a=Vl("CONSISTENCY");a&&pt(this,{encryptedTokenJarContents:a})}}
ot.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=(null==(c=b.Oa.context)?void 0:null==(d=c.request)?void 0:d.consistencyTokenJars)||[];var e;if(a=null==(e=a.responseContext)?void 0:e.consistencyTokenJar){e=v(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];pt(this,a)}};
function pt(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},1E3*c);
a.i&&Ul("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var qt=window.location.hostname.split(".").slice(-2).join(".");function rt(){var a=R("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===R("INNERTUBE_CLIENT_NAME")&&(this.h=st(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var tt;function ut(){tt=E("yt.clientLocationService.instance");tt||(tt=new rt,D("yt.clientLocationService.instance",tt));return tt}
m=rt.prototype;m.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.i?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(1E7*this.i.coords.latitude),a.client.locationInfo.longitudeE7=Math.floor(1E7*this.i.coords.longitude),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
m.handleResponse=function(a){var b;a=null==(b=a.responseContext)?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.i=void 0,"TVHTML5"===R("INNERTUBE_CLIENT_NAME")?(this.h=st(this))&&this.h.set("yt-location-playability-token",a,15552E3):Ul("YT_CL",JSON.stringify({loctok:a}),15552E3,qt,!0))};
function st(a){return void 0===a.h?new Vm("yt-client-location"):a.h}
m.clearLocationPlayabilityToken=function(a){"TVHTML5"===a?(this.h=st(this))&&this.h.remove("yt-location-playability-token"):Wl("YT_CL")};
m.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;"MWEB"===R("INNERTUBE_CLIENT_NAME")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
m.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null==a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};
m.createLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);return b};function vt(a,b){if(!a)return!1;var c,d=null==(c=U(a,xk))?void 0:c.signal;if(d&&b.mb)return!!b.mb[d];var e;if((c=null==(e=U(a,uk))?void 0:e.request)&&b.Ac)return!!b.Ac[c];for(var f in a)if(b.zc[f])return!0;return!1}
function wt(a,b){var c,d=null==(c=U(a,xk))?void 0:c.signal;if(d&&b.mb&&(c=b.mb[d]))return c();var e;if((c=null==(e=U(a,uk))?void 0:e.request)&&b.Ac&&(e=b.Ac[c]))return e();for(var f in a)if(b.zc[f]&&(a=b.zc[f]))return a()}
;function xt(a){return function(){return new a}}
;var zt={},At=(zt.WEB_UNPLUGGED="^unplugged/",zt.WEB_UNPLUGGED_ONBOARDING="^unplugged/",zt.WEB_UNPLUGGED_OPS="^unplugged/",zt.WEB_UNPLUGGED_PUBLIC="^unplugged/",zt.WEB_CREATOR="^creator/",zt.WEB_KIDS="^kids/",zt.WEB_EXPERIMENTS="^experiments/",zt.WEB_MUSIC="^music/",zt.WEB_REMIX="^music/",zt.WEB_MUSIC_EMBEDDED_PLAYER="^music/",zt.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",zt);
function Bt(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=At[b];if(c){var d=new RegExp(c),e=v(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries(At).forEach(function(g){var h=v(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=v(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function Ct(){}
Ct.prototype.m=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?Rl:c;var d=a.clickTrackingParams,e=this.l,f=!1;f=void 0===f?!1:f;e=void 0===e?!1:e;var g=R("INNERTUBE_CONTEXT");if(g){g=sb(g);S("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;"MWEB"===h.clientName&&(h.clientFormFactor=R("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||
1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=void 0===k?!1:k;am();var l="USER_INTERFACE_THEME_LIGHT";dm(165)?l="USER_INTERFACE_THEME_DARK":dm(174)?l="USER_INTERFACE_THEME_LIGHT":!S("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(l="USER_INTERFACE_THEME_DARK");k=k?l:nt()||l;h.userInterfaceTheme=k;if(!f){if(k=im())h.connectionType=
k;S("web_log_effective_connection_type")&&(k=jm())&&(g.client.effectiveConnectionType=k)}var n;if(S("web_log_memory_total_kbytes")&&(null==(n=C.navigator)?0:n.deviceMemory)){var r;n=null==(r=C.navigator)?void 0:r.deviceMemory;g.client.memoryTotalKbytes=""+1E6*n}S("web_gcf_hashes_innertube")&&(k=So())&&(r=k.coldConfigData,n=k.coldHashData,k=k.hotHashData,g.client.configInfo=g.client.configInfo||{},g.client.configInfo.coldConfigData=r,g.client.configInfo.coldHashData=n,g.client.configInfo.hotHashData=
k);r=bl(C.location.href);!S("web_populate_internal_geo_killswitch")&&r.internalcountrycode&&(h.internalGeo=r.internalcountrycode);"MWEB"===h.clientName||"WEB"===h.clientName?(h.mainAppWebInfo={graftUrl:C.location.href},S("kevlar_woffle")&&Sl.h&&(r=Sl.h,h.mainAppWebInfo.pwaInstallabilityStatus=!r.h&&r.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=Tl(),h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):
"TVHTML5"===h.clientName&&(!S("web_lr_app_quality_killswitch")&&(r=R("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:r})),r=R("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{certificationScope:r}));if(!S("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var t=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(V){}t=void 0}t&&(h.timeZone=t)}(t=R("EXPERIMENTS_TOKEN",""))?h.experimentsToken=
t:delete h.experimentsToken;t=il();ot.h||(ot.h=new ot);h=ot.h.h;r=[];n=0;for(var p in h)r[n++]=h[p];g.request=Object.assign({},g.request,{internalExperimentFlags:t,consistencyTokenJars:r});!S("web_prequest_context_killswitch")&&(p=R("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(g.request.externalPrequestContext=p);t=am();p=dm(58);t=t.get("gsml","");g.user=Object.assign({},g.user);p&&(g.user.enableSafetyMode=p);t&&(g.user.lockedSafetyMode=!0);S("warm_op_csn_cleanup")?e&&(f=Ns())&&(g.clientScreenNonce=f):
!f&&(f=Ns())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=E("yt.mdx.remote.remoteClient_"))g.remoteClient=d;ut().setLocationOnInnerTubeContext(g);try{var x=el(),y=x.bid;delete x.bid;g.adSignalsInfo={params:[],bid:y};var z=v(Object.entries(x));for(var H=z.next();!H.done;H=z.next()){var I=v(H.value),M=I.next().value,N=I.next().value;x=M;y=N;d=void 0;null==(d=g.adSignalsInfo.params)||d.push({key:x,value:""+y})}}catch(V){vs(V)}z=g}else vs(Error("Error: No InnerTubeContext shell provided in ytconfig.")),
z={};z={context:z};if(H=this.h(a)){this.i(z,H,b);var K;b="/youtubei/v1/"+Bt(this.j());(H=null==(K=U(a.commandMetadata,wk))?void 0:K.apiUrl)&&(b=H);K=b;(b=R("INNERTUBE_HOST_OVERRIDE"))&&(K=String(b)+String(dc(K)));b={};b.key=R("INNERTUBE_API_KEY");S("json_condensed_response")&&(b.prettyPrint="false");K=cl(K,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:K,kb:Zs(K),Oa:z,config:a};a.config.Wb?a.config.Wb.identity=c:a.config.Wb={identity:c};return a}vs(new km("Error: Failed to create Request from Command.",
a))};
da.Object.defineProperties(Ct.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!1}}});function Dt(){}
w(Dt,Ct);Dt.prototype.m=function(){return{input:"/getDatasyncIdsEndpoint",kb:Zs("/getDatasyncIdsEndpoint","GET"),Oa:{}}};
Dt.prototype.j=function(){return[]};
Dt.prototype.h=function(){};
Dt.prototype.i=function(){};var Et={},Ft=(Et.GET_DATASYNC_IDS=xt(Dt),Et);var Gt="absolute_experiments app conditional_experiments debugcss debugjs expflag forced_experiments pbj pbjreload sbb spf spfreload sr_bns_address sttick".split(" ");
function Ht(a,b){var c=void 0===c?!0:c;var d=R("VALID_SESSION_TEMPDATA_DOMAINS",[]),e=cc(window.location.href);e&&d.push(e);e=cc(a);if(0<=cb(d,e)||!e&&0==a.lastIndexOf("/",0))if(d=document.createElement("a"),Jh(d,a),a=d.href)if(a=dc(a),a=ec(a))if(c&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:Ns()},b)),f){var f=parseInt(f,10);isFinite(f)&&0<f&&It(a,b,f)}else It(a,b)}
function It(a,b,c){a=Jt(a);b=b?jc(b):"";c=c||5;$s()&&Ul(a,b,c)}
function Jt(a){if(S("st_skip_debug_params")){for(var b=v(Gt),c=b.next();!c.done;c=b.next())a=qc(a,c.value);return"ST-"+Zb(a).toString(36)}return"ST-"+Zb(a).toString(36)}
;function Kt(){try{return!!self.localStorage}catch(a){return!1}}
;function Lt(a){a=a.match(/(.*)::.*::.*/);if(null!==a)return a[1]}
function Mt(a){if(Kt()){var b=Object.keys(window.localStorage);b=v(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Lt(c);void 0===d||a.includes(d)||self.localStorage.removeItem(c)}}}
function Nt(){if(!Kt())return!1;var a=mm(),b=Object.keys(window.localStorage);b=v(b);for(var c=b.next();!c.done;c=b.next())if(c=Lt(c.value),void 0!==c&&c!==a)return!0;return!1}
;function Ot(){var a=!1;try{a=!!window.sessionStorage.getItem("session_logininfo")}catch(b){a=!0}return S("copy_login_info_to_st_cookie")&&("WEB"===R("INNERTUBE_CLIENT_NAME")||"WEB_CREATOR"===R("INNERTUBE_CLIENT_NAME"))&&a}
function Pt(a){if(R("LOGGED_IN",!0)&&Ot()){var b=R("VALID_SESSION_TEMPDATA_DOMAINS",[]);var c=cc(window.location.href);c&&b.push(c);c=cc(a);0<=cb(b,c)||!c&&0==a.lastIndexOf("/",0)?(b=dc(a),(b=ec(b))?(b=Jt(b),b=(b=Vl(b)||null)?al(b):{}):b=null):b=null;null==b&&(b={});c=b;var d=void 0;Ot()?(d||(d=R("LOGIN_INFO")),d?(c.session_logininfo=d,c=!0):c=!1):c=!1;c&&Ht(a,b)}}
;function Qt(a){var b=B.apply(1,arguments);if(!Rt(a)||b.some(function(d){return!Rt(d)}))throw Error("Only objects may be merged.");
b=v(b);for(var c=b.next();!c.done;c=b.next())St(a,c.value);return a}
function St(a,b){for(var c in b)if(Rt(b[c])){if(c in a&&!Rt(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});St(a[c],b[c])}else if(Tt(b[c])){if(c in a&&!Tt(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);Ut(a[c],b[c])}else a[c]=b[c];return a}
function Ut(a,b){b=v(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Rt(c)?a.push(St({},c)):Tt(c)?a.push(Ut([],c)):a.push(c);return a}
function Rt(a){return"object"===typeof a&&!Array.isArray(a)}
function Tt(a){return"object"===typeof a&&Array.isArray(a)}
;function Vt(a){var b;(b=E("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},D("ytcsi."+(a||"")+"data_",b));return b}
function Wt(){var a=Vt();a.info||(a.info={});return a.info}
function Xt(a){a=Vt(a);a.metadata||(a.metadata={});return a.metadata}
function Yt(a){a=Vt(a);a.tick||(a.tick={});return a.tick}
function Zt(a){a=Vt(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function $t(a){a=Zt(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function au(a){var b=Vt(a).nonce;b||(b=Ds(),Vt(a).nonce=b);return b}
;function bu(){var a=E("ytcsi.debug");a||(a=[],D("ytcsi.debug",a),D("ytcsi.reference",{}));return a}
function cu(a){a=a||"";var b=E("ytcsi.reference");b||(bu(),b=E("ytcsi.reference"));if(b[a])return b[a];var c=bu(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var W={},du=(W.auto_search="LATENCY_ACTION_AUTO_SEARCH",W.ad_to_ad="LATENCY_ACTION_AD_TO_AD",W.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",W["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",W.app_startup="LATENCY_ACTION_APP_STARTUP",W["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",W["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",W["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",W["asset.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS",
W["asset.composition"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION",W["asset.composition_ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_OWNERSHIP",W["asset.composition_policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_POLICY",W["asset.embeds"]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS",W["asset.issues"]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES",W["asset.licenses"]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES",W["asset.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA",W["asset.ownership"]=
"LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP",W["asset.policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY",W["asset.references"]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES",W["asset.shares"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SHARES",W["asset.sound_recordings"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS",W["asset_group.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_ASSETS",W["asset_group.campaigns"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CAMPAIGNS",W["asset_group.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CLAIMED_VIDEOS",
W["asset_group.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_METADATA",W["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",W.browse="LATENCY_ACTION_BROWSE",W.cast_splash="LATENCY_ACTION_CAST_SPLASH",W.channels="LATENCY_ACTION_CHANNELS",W.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",W["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",W["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",W["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",
W["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",W["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",W["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",W["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",W["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",W["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",W["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",W["channel.translations"]=
"LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",W["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",W["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",W.chips="LATENCY_ACTION_CHIPS",W["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",W["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",W["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",W.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",W.embed="LATENCY_ACTION_EMBED",
W.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",W.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",W.explore="LATENCY_ACTION_EXPLORE",W.home="LATENCY_ACTION_HOME",W.library="LATENCY_ACTION_LIBRARY",W.live="LATENCY_ACTION_LIVE",W.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",W.mini_app="LATENCY_ACTION_MINI_APP_PLAY",W.onboarding="LATENCY_ACTION_ONBOARDING",W.owner="LATENCY_ACTION_CREATOR_CMS_DASHBOARD",W["owner.allowlist"]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST",
W["owner.analytics"]="LATENCY_ACTION_CREATOR_CMS_ANALYTICS",W["owner.art_tracks"]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS",W["owner.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSETS",W["owner.asset_groups"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS",W["owner.bulk"]="LATENCY_ACTION_CREATOR_CMS_BULK_HISTORY",W["owner.campaigns"]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS",W["owner.channel_invites"]="LATENCY_ACTION_CREATOR_CMS_CHANNEL_INVITES",W["owner.channels"]="LATENCY_ACTION_CREATOR_CMS_CHANNELS",W["owner.claimed_videos"]=
"LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS",W["owner.claims"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",W["owner.claims.manual"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",W["owner.delivery"]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY",W["owner.delivery_templates"]="LATENCY_ACTION_CREATOR_CMS_DELIVERY_TEMPLATES",W["owner.issues"]="LATENCY_ACTION_CREATOR_CMS_ISSUES",W["owner.licenses"]="LATENCY_ACTION_CREATOR_CMS_LICENSES",W["owner.pitch_music"]="LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC",W["owner.policies"]=
"LATENCY_ACTION_CREATOR_CMS_POLICIES",W["owner.releases"]="LATENCY_ACTION_CREATOR_CMS_RELEASES",W["owner.reports"]="LATENCY_ACTION_CREATOR_CMS_REPORTS",W["owner.videos"]="LATENCY_ACTION_CREATOR_CMS_VIDEOS",W.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",W.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",W.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",W.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",W["playlist.videos"]="LATENCY_ACTION_CREATOR_PLAYLIST_VIDEO_LIST",
W["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",W["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",W.prebuffer="LATENCY_ACTION_PREBUFFER",W.prefetch="LATENCY_ACTION_PREFETCH",W.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",W.profile_switcher="LATENCY_ACTION_LOGIN",W.reel_watch="LATENCY_ACTION_REEL_WATCH",W.results="LATENCY_ACTION_RESULTS",W["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",W.search_ui="LATENCY_ACTION_SEARCH_UI",W.search_suggest="LATENCY_ACTION_SUGGEST",
W.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",W.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",W.seek="LATENCY_ACTION_PLAYER_SEEK",W.settings="LATENCY_ACTION_SETTINGS",W.store="LATENCY_ACTION_STORE",W.tenx="LATENCY_ACTION_TENX",W.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",W.watch="LATENCY_ACTION_WATCH",W.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",W["watch,watch7"]="LATENCY_ACTION_WATCH",W["watch,watch7_html5"]="LATENCY_ACTION_WATCH",W["watch,watch7ad"]="LATENCY_ACTION_WATCH",W["watch,watch7ad_html5"]=
"LATENCY_ACTION_WATCH",W.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",W.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",W["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",W["video.claims"]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS",W["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",W["video.copyright"]="LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT",W["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",W["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",W["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",
W["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",W["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",W["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",W["video.policy"]="LATENCY_ACTION_CREATOR_VIDEO_POLICY",W["video.rights_management"]="LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT",W["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",W.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",W.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",
W.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",W.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",W.gel_jspb_serialize="LATENCY_ACTION_GEL_JSPB_SERIALIZE",W),X={},eu=(X.ad_allowed="adTypesAllowed",X.yt_abt="adBreakType",X.ad_cpn="adClientPlaybackNonce",X.ad_docid="adVideoId",X.yt_ad_an="adNetworks",X.ad_at="adType",X.aida="appInstallDataAgeMs",X.browse_id="browseId",X.p="httpProtocol",X.t="transportProtocol",X.cpn="clientPlaybackNonce",X.ccs="creatorInfo.creatorCanaryState",X.ctop=
"creatorInfo.topEntityType",X.csn="clientScreenNonce",X.docid="videoId",X.GetHome_rid="requestIds",X.GetSearch_rid="requestIds",X.GetPlayer_rid="requestIds",X.GetWatchNext_rid="requestIds",X.GetBrowse_rid="requestIds",X.GetLibrary_rid="requestIds",X.is_continuation="isContinuation",X.is_nav="isNavigation",X.b_p="kabukiInfo.browseParams",X.is_prefetch="kabukiInfo.isPrefetch",X.is_secondary_nav="kabukiInfo.isSecondaryNav",X.nav_type="kabukiInfo.navigationType",X.prev_browse_id="kabukiInfo.prevBrowseId",
X.query_source="kabukiInfo.querySource",X.voz_type="kabukiInfo.vozType",X.yt_lt="loadType",X.mver="creatorInfo.measurementVersion",X.yt_ad="isMonetized",X.nr="webInfo.navigationReason",X.nrsu="navigationRequestedSameUrl",X.pnt="performanceNavigationTiming",X.prt="playbackRequiresTap",X.plt="playerInfo.playbackType",X.pis="playerInfo.playerInitializedState",X.paused="playerInfo.isPausedOnLoad",X.yt_pt="playerType",X.fmt="playerInfo.itag",X.yt_pl="watchInfo.isPlaylist",X.yt_pre="playerInfo.preloadType",
X.yt_ad_pr="prerollAllowed",X.pa="previousAction",X.yt_red="isRedSubscriber",X.rce="mwebInfo.responseContentEncoding",X.rc="resourceInfo.resourceCache",X.scrh="screenHeight",X.scrw="screenWidth",X.st="serverTimeMs",X.ssdm="shellStartupDurationMs",X.br_trs="tvInfo.bedrockTriggerState",X.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",X.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",X.label="tvInfo.label",X.is_mdx="tvInfo.isMdx",X.preloaded="tvInfo.isPreloaded",X.aac_type="tvInfo.authAccessCredentialType",
X.upg_player_vis="playerInfo.visibilityState",X.query="unpluggedInfo.query",X.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",X.yt_vst="videoStreamType",X.vph="viewportHeight",X.vpw="viewportWidth",X.yt_vis="isVisible",X.rcl="mwebInfo.responseContentLength",X.GetSettings_rid="requestIds",X.GetTrending_rid="requestIds",X.GetMusicSearchSuggestions_rid="requestIds",X.REQUEST_ID="requestIds",X),fu="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),
gu={},hu=(gu.ccs="CANARY_STATE_",gu.mver="MEASUREMENT_VERSION_",gu.pis="PLAYER_INITIALIZED_STATE_",gu.yt_pt="LATENCY_PLAYER_",gu.pa="LATENCY_ACTION_",gu.ctop="TOP_ENTITY_TYPE_",gu.yt_vst="VIDEO_STREAM_TYPE_",gu),iu="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function ju(a,b,c){c=Zt(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in eu){c=eu[a];0<=cb(fu,c)&&(b=!!b);a in hu&&"string"===typeof b&&(b=hu[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return Qt({},d)}0<=cb(iu,a)||ws(new km("Unknown label logged with GEL CSI",a))}
;function ku(a,b){Xo.call(this,1,arguments);this.timer=b}
w(ku,Xo);var lu=new Yo("aft-recorded",ku);var mu=C.ytLoggingLatencyUsageStats_||{};D("ytLoggingLatencyUsageStats_",mu);function nu(){this.h=0}
function ou(){nu.h||(nu.h=new nu);return nu.h}
nu.prototype.tick=function(a,b,c,d){pu(this,"tick_"+a+"_"+b)||dn("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
nu.prototype.info=function(a,b,c){var d=Object.keys(a).join("");pu(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,dn("latencyActionInfo",a,{cttAuthInfo:c}))};
nu.prototype.jspbInfo=function(){};
nu.prototype.span=function(a,b,c){var d=Object.keys(a).join("");pu(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,dn("latencyActionSpan",a,{cttAuthInfo:c}))};
function pu(a,b){mu[b]=mu[b]||{count:0};var c=mu[b];c.count++;c.time=T();a.h||(a.h=om(function(){var d=T(),e;for(e in mu)mu[e]&&6E4<d-mu[e].time&&delete mu[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new km("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||ws(c)),!0):!1}
;var qu=window;function ru(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function su(){var a;if(S("csi_use_performance_navigation_timing")||S("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=null==Y?void 0:null==(a=Y.getEntriesByType)?void 0:null==(b=a.call(Y,"navigation"))?void 0:null==(c=b[0])?void 0:null==(d=c.toJSON)?void 0:d.call(c);e?(e.requestStart=tu(e.requestStart),e.responseEnd=tu(e.responseEnd),e.redirectStart=tu(e.redirectStart),e.redirectEnd=tu(e.redirectEnd),e.domainLookupEnd=tu(e.domainLookupEnd),e.connectStart=tu(e.connectStart),e.connectEnd=
tu(e.connectEnd),e.responseStart=tu(e.responseStart),e.secureConnectionStart=tu(e.secureConnectionStart),e.domainLookupStart=tu(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=Y.timing}else a=Y.timing;return a}
function tu(a){return Math.round(uu()+a)}
function uu(){return(S("csi_use_time_origin")||S("csi_use_time_origin_tvhtml5"))&&Y.timeOrigin?Math.floor(Y.timeOrigin):Y.timing.navigationStart}
var Y=qu.performance||qu.mozPerformance||qu.msPerformance||qu.webkitPerformance||new ru;var vu=!1,wu={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="preload"][name="player/embed"]':"pej",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",
'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",
'script[name="mobile_blazer_watch_mod"]':"mbwj"};Ua(Y.clearResourceTimings||Y.webkitClearResourceTimings||Y.mozClearResourceTimings||Y.msClearResourceTimings||Y.oClearResourceTimings||ab,Y);function xu(a,b,c){if(null!==b){if("yt_lt"===a){var d="string"===typeof b?b:""+b;Xt(c).loadType=d}(a=ju(a,b,c))&&yu(a,c)}}
function yu(a,b){if(!S("web_csi_action_sampling_enabled")||!Vt(b).actionDisabled){var c=cu(b||"");Qt(c.info,a);a.loadType&&(c=a.loadType,Xt(b).loadType=c);Qt($t(b),a);c=au(b);b=Vt(b).cttAuthInfo;ou().info(a,c,b)}}
function zu(){var a,b,c,d;return(null!=(d=null==jr().resolve(new er(Oo))?void 0:null==(a=Po())?void 0:null==(b=a.loggingHotConfig)?void 0:null==(c=b.csiConfig)?void 0:c.debugTicks)?d:[]).map(function(e){return Object.values(e)[0]})}
function Au(a,b,c){if(!S("web_csi_action_sampling_enabled")||!Vt(c).actionDisabled){var d=au(c),e;if(e=S("web_csi_debug_sample_enabled")&&d)if(!1===Vt(c).debugTicksExcludedLogged)e=!1;else if(0===zu().length)e=Vt(c).debugTicksExcludedLogged=!1;else{var f,g,h;e=(null==jr().resolve(new er(Oo))?void 0:null==(f=Po())?void 0:null==(g=f.loggingHotConfig)?void 0:null==(h=g.csiConfig)?void 0:h.debugSampleWeight)||0;if(f=0!==e)b:{f=zu();if(0<f.length)for(g=0;g<f.length;g++)if(a===f[g]){f=!0;break b}f=!1}if(f){for(g=
f=0;g<d.length;g++)f=31*f+d.charCodeAt(g),g<d.length-1&&(f%=Math.pow(2,47));e=0!==f%1E5%e;Vt(c).debugTicksExcludedLogged||(f={},f.debugTicksExcluded=e,yu(f,c));Vt(c).debugTicksExcludedLogged=!0}else e=!1}if(!e){b||"_"===a[0]||(e=a,Y.mark&&(0==e.lastIndexOf("mark_",0)||(e="mark_"+e),c&&(e+=" ("+c+")"),Y.mark(e)));e=cu(c||"");e.tick[a]=b||T();if(e.callback&&e.callback[a])for(e=v(e.callback[a]),f=e.next();!f.done;f=e.next())f=f.value,f();e=Zt(c);e.gelTicks&&(e.gelTicks[a]=!0);f=Yt(c);e=b||T();S("log_repeated_ytcsi_ticks")?
a in f||(f[a]=e):f[a]=e;f=Vt(c).cttAuthInfo;"_start"===a?(a=ou(),pu(a,"baseline_"+d)||dn("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:f})):ou().tick(a,d,b,f);Bu(c);return e}}}
function Cu(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=Aq+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Du(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);Xb()&&a.setAttribute("nonce",Xb());return c?(a=Y.getEntriesByName(c))&&a[0]&&(a=a[0],c=uu(),Au("rsf_"+b,c+Math.round(a.fetchStart)),Au("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function Eu(){var a=window.location.protocol,b=Y.getEntriesByType("resource");b=eb(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=gb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Au("wffs",tu(b.startTime)),Au("wffe",tu(b.responseEnd)))}
function Fu(a){var b=Gu("aft",a);if(b)return b;b=R((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=Gu(b[d],a);if(e)return e}return NaN}
function Gu(a,b){if(a=Yt(b)[a])return"number"===typeof a?a:a[a.length-1]}
function Bu(a){var b=Gu("_start",a),c=Fu(a);b&&c&&!vu&&(cp(lu,new ku(Math.round(c-b),a)),vu=!0)}
function Hu(a,b){for(var c=v(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!Hu(a[d],b[d]))return!1;return!0}
function Iu(){if(Y.getEntriesByType){var a=Y.getEntriesByType("paint");if(a=hb(a,function(b){return"first-paint"===b.name}))return tu(a.startTime)}a=Y.timing;
return a.De?Math.max(0,a.De):0}
;function Ju(a,b){Sk(function(){cu("").info.actionType=a;b&&Ok("TIMING_AFT_KEYS",b);Ok("TIMING_ACTION",a);var c=R("TIMING_INFO",{}),d;for(d in c)c.hasOwnProperty(d)&&xu(d,c[d]);c={isNavigation:!0,actionType:du[R("TIMING_ACTION")]||"LATENCY_ACTION_UNKNOWN"};if(d=R("PREVIOUS_ACTION"))c.previousAction=du[d]||"LATENCY_ACTION_UNKNOWN";if(d=R("CLIENT_PROTOCOL"))c.httpProtocol=d;if(d=R("CLIENT_TRANSPORT"))c.transportProtocol=d;(d=Ns())&&"UNDEFINED_CSN"!==d&&(c.clientScreenNonce=d);d=Cu();if(1===d||-1===d)c.isVisible=
!0;Xt();Wt();c.loadType="cold";d=Wt();var e=su(),f=uu(),g=R("CSI_START_TIMESTAMP_MILLIS",0);0<g&&!S("embeds_web_enable_csi_start_override_killswitch")&&(f=g);f&&(Au("srt",e.responseStart),1!==d.prerender&&Au("_start",f,void 0));d=Iu();0<d&&Au("fpt",d);d=su();d.isPerformanceNavigationTiming&&yu({performanceNavigationTiming:!0});Au("nreqs",d.requestStart,void 0);Au("nress",d.responseStart,void 0);Au("nrese",d.responseEnd,void 0);0<d.redirectEnd-d.redirectStart&&(Au("nrs",d.redirectStart,void 0),Au("nre",
d.redirectEnd,void 0));0<d.domainLookupEnd-d.domainLookupStart&&(Au("ndnss",d.domainLookupStart,void 0),Au("ndnse",d.domainLookupEnd,void 0));0<d.connectEnd-d.connectStart&&(Au("ntcps",d.connectStart,void 0),Au("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=uu()&&0<d.connectEnd-d.secureConnectionStart&&(Au("nstcps",d.secureConnectionStart,void 0),Au("ntcpe",d.connectEnd,void 0));Y&&"getEntriesByType"in Y&&Eu();d=[];if(document.querySelector&&Y&&Y.getEntriesByName)for(var h in wu)wu.hasOwnProperty(h)&&
(e=wu[h],Du(h,e)&&d.push(e));if(0<d.length)for(c.resourceInfo=[],h=v(d),d=h.next();!d.done;d=h.next())c.resourceInfo.push({resourceCache:d.value});yu(c);c=Wt();h=$t();if("cold"===Xt().loadType&&("cold"===c.yt_lt||"cold"===h.loadType)){d=Yt();e=Zt();e=e.gelTicks?e.gelTicks:e.gelTicks={};for(var k in d)if(!(k in e))if("number"===typeof d[k])Au(k,Gu(k));else if(S("log_repeated_ytcsi_ticks"))for(f=v(d[k]),g=f.next();!g.done;g=f.next())g=g.value,Au(k.slice(1),g);k={};d=!1;e=v(Object.keys(c));for(f=e.next();!f.done;f=
e.next())f=f.value,(f=ju(f,c[f]))&&!Hu($t(),f)&&(Qt(h,f),Qt(k,f),d=!0);d&&yu(k)}D("ytglobal.timingready_",!0);k=R("TIMING_ACTION");E("ytglobal.timingready_")&&k&&Ku()&&Fu()&&Bu()})()}
function Lu(a,b,c,d){Sk(xu)(a,b,c,d)}
function Mu(a,b,c){return Sk(Au)(a,b,c)}
function Ku(){return Sk(function(){return"_start"in Yt()})()}
function Nu(){Sk(function(){var a=au();requestAnimationFrame(function(){setTimeout(function(){a===au()&&Mu("ol",void 0,void 0)},0)})})()}
var Ou=window;Ou.ytcsi&&(Ou.ytcsi.info=Lu,Ou.ytcsi.tick=Mu);var Pu="tokens consistency mss client_location entities adblock_detection response_received_commands store PLAYER_PRELOAD".split(" "),Qu=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse"];function Ru(a,b,c,d){this.j=a;this.aa=b;this.m=c;this.l=d;this.i=void 0;this.h=new Map;a.mb||(a.mb={});a.mb=Object.assign({},Ft,a.mb)}
function Su(a,b,c,d){if(void 0!==Ru.h){if(d=Ru.h,a=[a!==d.j,b!==d.aa,c!==d.m,!1,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new km("InnerTubeTransportService is already initialized",a);
}else Ru.h=new Ru(a,b,c,d)}
function Tu(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?Rl:c;var d=wt(b,a.j);if(!d)return Xd(new km("Error: No request builder found for command.",b));var e=d.m(b,void 0,c);return e?(Pt(e.input),new Rd(function(f){var g,h,k;return A(function(l){if(1==l.h){h="cors"===(null==(g=e.kb)?void 0:g.mode)?"cors":void 0;if(a.m.cf){var n=e.config,r;n=null==n?void 0:null==(r=n.Wb)?void 0:r.sessionIndex;r=Ql(0,{sessionIndex:n});k=Object.assign({},Uu(h),r);return l.v(2)}return l.yield(Vu(e.config,
h),3)}2!=l.h&&(k=l.i);f(Wu(a,e,k));l.h=0})})):Xd(new km("Error: Failed to build request for command.",b))}
function Xu(a,b,c){var d;if(b&&!(null==b?0:null==(d=b.fg)?0:d.jg)&&a.l){d=v(Pu);for(var e=d.next();!e.done;e=d.next())e=e.value,a.l[e]&&a.l[e].handleResponse(b,c)}}
function Wu(a,b,c){var d,e,f,g,h,k,l,n,r,t,p,x,y,z,H,I,M,N,K,V,Z,ha,qa,na,Ia,Jg,Pq,Qq,Rq;return A(function(ka){switch(ka.h){case 1:ka.v(2);break;case 3:if((d=ka.i)&&!d.isExpired())return ka.return(Promise.resolve(d.h()));case 2:if(!(null==(e=b)?0:null==(f=e.Oa)?0:f.context)){ka.v(4);break}g=b.Oa.context;ka.v(5);break;case 5:h=v([]),k=h.next();case 7:if(k.done){ka.v(4);break}l=k.value;return ka.yield(l.cg(g),8);case 8:k=h.next();ka.v(7);break;case 4:if(null==(n=a.i)||!n.gg(b.input,b.Oa)){ka.v(11);
break}return ka.yield(a.i.Yf(b.input,b.Oa),12);case 12:return r=ka.i,S("kevlar_process_local_innertube_responses_killswitch")||Xu(a,r,b),ka.return(r);case 11:return(x=null==(p=b.config)?void 0:p.Qa)&&a.h.has(x)&&S("web_memoize_inflight_requests")?t=a.h.get(x):(y=JSON.stringify(b.Oa),I=null!=(H=null==(z=b.kb)?void 0:z.headers)?H:{},b.kb=Object.assign({},b.kb,{headers:Object.assign({},I,c)}),M=Object.assign({},b.kb),"POST"===b.kb.method&&(M=Object.assign({},M,{body:y})),(null==(N=b.config)?0:N.Me)&&
Mu(b.config.Me),K=function(){return a.aa.fetch(b.input,M,b.config)},t=K(),x&&a.h.set(x,t)),ka.yield(t,13);
case 13:if((V=ka.i)&&"error"in V&&(null==(Z=V)?0:null==(ha=Z.error)?0:ha.details))for(qa=V.error.details,na=v(qa),Ia=na.next();!Ia.done;Ia=na.next())Jg=Ia.value,(Pq=Jg["@type"])&&-1<Qu.indexOf(Pq)&&(delete Jg["@type"],V=Jg);x&&a.h.has(x)&&a.h.delete(x);(null==(Qq=b.config)?0:Qq.Ne)&&Mu(b.config.Ne);if(V||null==(Rq=a.i)||!Rq.Qf(b.input,b.Oa)){ka.v(14);break}return ka.yield(a.i.Xf(b.input,b.Oa),15);case 15:V=ka.i;case 14:return Xu(a,V,b),ka.return(V||void 0)}})}
function Vu(a,b){var c,d,e,f;return A(function(g){if(1==g.h){e=null==(c=a)?void 0:null==(d=c.Wb)?void 0:d.sessionIndex;var h=g.yield;var k=Wd(Ql(0,{sessionIndex:e}));return h.call(g,k,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},Uu(b),f)))})}
function Uu(a){var b={"Content-Type":"application/json"};R("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=R("EOM_VISITOR_DATA"):R("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=R("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=R("LOGGED_IN",!1);"cors"!==a&&((a=R("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=R("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=R("CHROME_CONNECTED_HEADER"))&&(b["X-Youtube-Chrome-Connected"]=a),(a=R("DOMAIN_ADMIN_STATE"))&&
(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var Yu=new dr("INNERTUBE_TRANSPORT_TOKEN");var Zu=["share/get_web_player_share_panel"],$u=["feedback"],av=["notification/modify_channel_preference"],bv=["browse/edit_playlist"],cv=["subscription/subscribe"],dv=["subscription/unsubscribe"];function ev(){}
w(ev,Ct);ev.prototype.j=function(){return cv};
ev.prototype.h=function(a){return U(a,Fk)||void 0};
ev.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
da.Object.defineProperties(ev.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function fv(){}
w(fv,Ct);fv.prototype.j=function(){return dv};
fv.prototype.h=function(a){return U(a,Ek)||void 0};
fv.prototype.i=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
da.Object.defineProperties(fv.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function gv(){}
w(gv,Ct);gv.prototype.j=function(){return $u};
gv.prototype.h=function(a){return U(a,zk)||void 0};
gv.prototype.i=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
da.Object.defineProperties(gv.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function hv(){}
w(hv,Ct);hv.prototype.j=function(){return av};
hv.prototype.h=function(a){return U(a,Dk)||void 0};
hv.prototype.i=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function iv(){}
w(iv,Ct);iv.prototype.j=function(){return bv};
iv.prototype.h=function(a){return U(a,Ck)||void 0};
iv.prototype.i=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function jv(){}
w(jv,Ct);jv.prototype.j=function(){return Zu};
jv.prototype.h=function(a){return U(a,Bk)};
jv.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var kv=new dr("NETWORK_SLI_TOKEN");function lv(a){this.h=a}
lv.prototype.fetch=function(a,b){var c=this,d,e,f;return A(function(g){c.h&&(d=ac(bc(5,qc(a,"key")))||"/UNKNOWN_PATH",c.h.start(d));e=b;S("wug_networking_gzip_request")&&(e=up(b));f=new window.Request(a,e);return S("web_fetch_promise_cleanup_killswitch")?g.return(Promise.resolve(fetch(f).then(function(h){return c.handleResponse(h)}).catch(function(h){ws(h)}))):g.return(fetch(f).then(function(h){return c.handleResponse(h)}).catch(function(h){ws(h)}))})};
lv.prototype.handleResponse=function(a){var b=a.text().then(function(c){return JSON.parse(c.replace(")]}'",""))});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Tf(),b=b.then(function(c){ws(new km("Error: API fetch failed",a.status,a.url,c));return Object.assign({},c,{errorMetadata:{status:a.status}})}));
return b};
lv[cr]=[new er(kv)];var mv=new dr("NETWORK_MANAGER_TOKEN");var nv;function ov(){var a=pv,b=qv,c=rv;this.l=sv;this.navigate=a;this.i=b;this.j=c;this.h=new Set}
function tv(a,b,c){if(uv(b))vv(a,b,c);else{var d=a.l(b,c);if(null==c?0:c.yc)d.yc=c.yc;0===d.type?a.navigate?wv(d.command)?xv(a,d.command)||(S("logging_avoid_blocking_during_navigation")&&Ar().transition("application_navigating"),b=a.navigate(d)||[],$d(b).then(function(){a.h.delete(d.command)})):vs(Error("Error: Command handler page requests need to specify a url.")):vs(Error("Error: Command handler navigate function was called but not set.")):1===d.type?a.i?xv(a,d.command)||(b=a.i(d),$d(b).then(function(){a.h.delete(d.command)})):
vs(Error("Error: Command handler handle service request function was called but not set.")):2===d.type&&(a.j?a.j(d):vs(Error("Error: Command handler send action was called but not set.")))}}
function xv(a,b){if(a.h.has(b))return!0;a.h.add(b);return!1}
function uv(a){var b=!!U(a,sk),c;a="CLIENT_SIGNAL"===(null==(c=U(a,xk))?void 0:c.signal);return b||a}
function vv(a,b,c){var d=U(b,sk);if(d)var e=(null==d?void 0:d.commands)||[];else{var f;if("CLIENT_SIGNAL"===(null==(f=U(b,xk))?void 0:f.signal)){var g;e=(null==(g=U(b,xk))?void 0:g.actions)||[]}}if(e)for(b=v(e),e=b.next();!e.done;e=b.next()){e=e.value;try{tv(a,e,c)}catch(h){h instanceof Error&&vs(h)}}else vs(Error("Could not handle the meta command."))}
function wv(a){var b;return!(null==(b=U(null==a?void 0:a.commandMetadata,wk))||!b.url)}
;function yv(){var a,b,c;return A(function(d){if(1==d.h)return a=jr().resolve(Yu),a?d.yield(Tu(a),2):(ws(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return ws(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.Rf;return d.return(c)}ws(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;var zv=C.caches,Av;function Bv(a){var b=a.indexOf(":");return-1===b?{yd:a}:{yd:a.substring(0,b),datasyncId:a.substring(b+1)}}
function Cv(){return A(function(a){if(void 0!==Av)return a.return(Av);Av=new Promise(function(b){var c;return A(function(d){switch(d.h){case 1:return za(d,2),d.yield(zv.open("test-only"),4);case 4:return d.yield(zv.delete("test-only"),5);case 5:d.h=3;d.l=0;break;case 2:if(c=Aa(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(Av)})}
function Dv(a){var b,c,d,e,f,g,h;A(function(k){if(1==k.h)return k.yield(Cv(),2);if(3!=k.h){if(!k.i)return k.return(!1);b=[];return k.yield(zv.keys(),3)}c=k.i;d=v(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=Bv(f),h=g.datasyncId,!h||a.includes(h)||b.push(zv.delete(f));return k.return(Promise.all(b).then(function(l){return l.some(function(n){return n})}))})}
function Ev(){var a,b,c,d,e,f,g;return A(function(h){if(1==h.h)return h.yield(Cv(),2);if(3!=h.h){if(!h.i)return h.return(!1);a=mm("cache contains other");return h.yield(zv.keys(),3)}b=h.i;c=v(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=Bv(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Fv(){yv().then(function(a){a&&(to(a),Dv(a),Mt(a))})}
function Gv(){var a=new mq;pi.oa(function(){var b,c,d,e;return A(function(f){switch(f.h){case 1:if(S("ytidb_clear_optimizations_killswitch")){f.v(2);break}b=mm("clear");if(b.startsWith("V")&&b.endsWith("||")){var g=[b];to(g);Dv(g);Mt(g);return f.return()}c=Nt();return f.yield(Ev(),3);case 3:return d=f.i,f.yield(uo(),4);case 4:if(e=f.i,!c&&!d&&!e)return f.return();case 2:a.wa()?Fv():a.h.add("publicytnetworkstatus-online",Fv,!0,void 0,void 0),f.h=0}})})}
;var Oh=fa(["data-"]);function Hv(a){a&&(a.dataset?a.dataset[Iv("loaded")]="true":Nh(a))}
function Jv(a,b){return a?a.dataset?a.dataset[Iv(b)]:a.getAttribute("data-"+b):null}
var Kv={};function Iv(a){return Kv[a]||(Kv[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Lv=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,Mv=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function Nv(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(Lv,""),c=c.replace(Mv,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else Ov(a,b,c)}
function Ov(a,b,c){c=void 0===c?null:c;var d=Pv(a),e=document.getElementById(d),f=e&&Jv(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=Xq(d,b),b=""+Pa(b),Qv[b]=f),g||(e=Rv(a,d,function(){if(!Jv(e,"loaded")){Hv(e);$q(d);var h=Va(ar,d);ml(h,0)}},c)))}
function Rv(a,b,c,d){d=void 0===d?null:d;var e=Dd("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Th(e,ok(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function Sv(a){a=Pv(a);var b=document.getElementById(a);b&&(ar(a),b.parentNode.removeChild(b))}
function Tv(a,b){a&&b&&(a=""+Pa(b),(a=Qv[a])&&Zq(a))}
function Pv(a){var b=document.createElement("a");Jh(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+Zb(a)}
var Qv={};var Uv=[],Vv=!1;function Wv(){if(!S("disable_biscotti_fetch_for_ad_blocker_detection")&&!S("disable_biscotti_fetch_entirely_for_all_web_clients")&&$s()){var a=R("PLAYER_VARS",{});if("1"!=pb(a)&&!at(a)){var b=function(){Vv=!0;"google_ad_status"in window?Ok("DCLKSTAT",1):Ok("DCLKSTAT",2)};
try{Nv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Uv.push(pi.oa(function(){if(!(Vv||"google_ad_status"in window)){try{Tv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Vv=!0;Ok("DCLKSTAT",3)}},5E3))}}}
function Xv(){var a=Number(R("DCLKSTAT",0));return isNaN(a)?0:a}
;function Yv(a){sr.call(this,void 0===a?"document_active":a);var b=this;this.l=10;this.h=new Map;this.transitions=[{from:"document_active",to:"document_disposed_preventable",action:this.la},{from:"document_active",to:"document_disposed",action:this.m},{from:"document_disposed_preventable",to:"document_disposed",action:this.m},{from:"document_disposed_preventable",to:"flush_logs",action:this.G},{from:"document_disposed_preventable",to:"document_active",action:this.i},{from:"document_disposed",to:"flush_logs",
action:this.G},{from:"document_disposed",to:"document_active",action:this.i},{from:"document_disposed",to:"document_disposed",action:function(){}},
{from:"flush_logs",to:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
w(Yv,sr);Yv.prototype.la=function(a,b){if(!this.h.get("document_disposed_preventable")){a(null==b?void 0:b.event);var c,d;if((null==b?0:null==(c=b.event)?0:c.defaultPrevented)||(null==b?0:null==(d=b.event)?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
Yv.prototype.m=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(null==b?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
Yv.prototype.G=function(a,b){a(null==b?void 0:b.event);this.transition("document_active")};
Yv.prototype.i=function(){this.h=new Map};function Zv(a){sr.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",to:"document_visible",action:this.i},{from:"document_visibility_unknown",to:"document_hidden",action:this.h},{from:"document_visibility_unknown",to:"document_foregrounded",action:this.G},{from:"document_visibility_unknown",to:"document_backgrounded",action:this.m},{from:"document_visible",to:"document_hidden",action:this.h},{from:"document_visible",to:"document_foregrounded",
action:this.G},{from:"document_visible",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_hidden",action:this.h},{from:"document_foregrounded",to:"document_foregrounded",action:this.G},{from:"document_hidden",to:"document_visible",action:this.i},{from:"document_hidden",to:"document_backgrounded",action:this.m},{from:"document_hidden",to:"document_hidden",action:this.h},{from:"document_backgrounded",to:"document_hidden",
action:this.h},{from:"document_backgrounded",to:"document_backgrounded",action:this.m},{from:"document_backgrounded",to:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
S("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
w(Zv,sr);Zv.prototype.i=function(a,b){a(null==b?void 0:b.event);S("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
Zv.prototype.h=function(a,b){a(null==b?void 0:b.event);S("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
Zv.prototype.m=function(a,b){a(null==b?void 0:b.event)};
Zv.prototype.G=function(a,b){a(null==b?void 0:b.event)};function $v(){this.l=new Yv;this.m=new Zv}
$v.prototype.install=function(){var a=B.apply(0,arguments),b=this;a.forEach(function(c){b.l.install(c)});
a.forEach(function(c){b.m.install(c)})};function aw(a){Xo.call(this,1,arguments);this.csn=a}
w(aw,Xo);var fp=new Yo("screen-created",aw),bw=[],cw=0,dw=new Map,ew=new Map,fw=new Map;
function gw(a,b,c,d,e){e=void 0===e?!1:e;for(var f=hw({cttAuthInfo:Ps(b)||void 0},b),g=v(d),h=g.next();!h.done;h=g.next()){h=h.value;var k=h.getAsJson();(nb(k)||!k.trackingParams&&!k.veType)&&ws(Error("Child VE logged with no data"));if(S("no_client_ve_attach_unless_shown")){var l=iw(h,b);if(k.veType&&!ew.has(l)&&!fw.has(l)&&!e){dw.set(l,[a,b,c,h]);return}h=iw(c,b);dw.has(h)?jw(c,b):fw.set(h,!0)}}d=d.filter(function(n){n.csn!==b?(n.csn=b,n=!0):n=!1;return n});
c={csn:b,parentVe:c.getAsJson(),childVes:fb(d,function(n){return n.getAsJson()})};
"UNDEFINED_CSN"===b?kw("visualElementAttached",f,c):a?ns("visualElementAttached",c,a,f):dn("visualElementAttached",c,f)}
function kw(a,b,c){bw.push({payloadName:a,payload:c,Wf:void 0,options:b});cw||(cw=gp())}
function hp(a){if(bw){for(var b=v(bw),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,dn(c.payloadName,c.payload,c.options));bw.length=0}cw=0}
function iw(a,b){return""+a.getAsJson().veType+a.getAsJson().veCounter+b}
function jw(a,b){a=iw(a,b);dw.has(a)&&(b=dw.get(a)||[],gw(b[0],b[1],b[2],[b[3]],!0),dw.delete(a))}
function hw(a,b){S("log_sequence_info_on_gel_web")&&(a.sequenceGroup=b);return a}
;function lw(){this.l=[];this.i=new Map;this.h=new Map;this.j=new Set}
lw.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=void 0===c?0:c;if(d)if(c=Ns(void 0===c?0:c)){a=this.client;d=new Gs({trackingParams:d});var e=void 0;if(S("no_client_ve_attach_unless_shown")){var f=iw(d,c);ew.set(f,!0);jw(d,c)}e=e||"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";f=hw({cttAuthInfo:Ps(c)||void 0},c);d={csn:c,ve:d.getAsJson(),gestureType:e};b&&(d.clientData=b);"UNDEFINED_CSN"===c?kw("visualElementGestured",f,d):a?ns("visualElementGestured",d,a,f):dn("visualElementGestured",
d,f);b=!0}else b=!1;else b=!1;return b};
lw.prototype.stateChanged=function(a,b,c){this.visualElementStateChanged(new Gs({trackingParams:a}),b,void 0===c?0:c)};
lw.prototype.visualElementStateChanged=function(a,b,c){c=void 0===c?0:c;if(0===c&&this.j.has(c))this.l.push([a,b]);else{var d=c;d=void 0===d?0:d;c=Ns(d);a||(a=(a=Ks(void 0===d?0:d))?new Gs({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null);var e=a;c&&e&&(a=this.client,d=hw({cttAuthInfo:Ps(c)||void 0},c),b={csn:c,ve:e.getAsJson(),clientData:b},"UNDEFINED_CSN"===c?kw("visualElementStateChanged",d,b):a?ns("visualElementStateChanged",b,a,d):dn("visualElementStateChanged",b,d))}};
function mw(a,b){if(void 0===b)for(var c=Ms(),d=0;d<c.length;d++)void 0!==c[d]&&mw(a,c[d]);else a.i.forEach(function(e,f){(f=a.h.get(f))&&gw(a.client,b,f,e)}),a.i.clear(),a.h.clear(),a.m=void 0}
;function nw(){$v.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));S("combine_ve_grafts")&&(a={},this.install((a.document_disposed={callback:this.i},a)));a={};this.install((a.flush_logs={callback:this.j},a))}
w(nw,$v);nw.prototype.j=function(){dn("finalPayload",{csn:Ns()})};
nw.prototype.h=function(){As(Bs)};
nw.prototype.i=function(){var a=mw;lw.h||(lw.h=new lw);a(lw.h)};function ow(){}
function pw(){var a=E("ytglobal.storage_");a||(a=new ow,D("ytglobal.storage_",a));return a}
ow.prototype.estimate=function(){var a,b,c;return A(function(d){a=navigator;return(null==(b=a.storage)?0:b.estimate)?d.return(a.storage.estimate()):(null==(c=a.webkitTemporaryStorage)?0:c.queryUsageAndQuota)?d.return(qw()):d.return()})};
function qw(){var a=navigator;return new Promise(function(b,c){var d;null!=(d=a.webkitTemporaryStorage)&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
D("ytglobal.storageClass_",ow);function bn(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=hl("ytidb_transaction_ended_event_rate_limit_session",.2)}
bn.prototype.Rb=function(a){this.handleError(a)};
bn.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":S("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":S("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":rw(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=hl("ytidb_transaction_ended_event_rate_limit_transaction",.1)&&this.h("idbTransactionEnded",
b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function rw(a,b){pw().estimate().then(function(c){c=Object.assign({},b,{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:sw(null==c?void 0:c.usage),deviceStorageQuotaMbytes:sw(null==c?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function sw(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;function tw(a){this.args=void 0===a?null:a;this.returnValue=[]}
;var uw=new Map;function vw(a,b){if(!a)return null;a=Object.keys(a);a=v(a);for(var c=a.next();!c.done;c=a.next()){c=c.value;var d=c.toLowerCase();if(-1<d.indexOf(b,d.length-b.length))return c}return null}
;function ww(a,b,c){var d;d||(d={bubbles:!0,cancelable:!1,composed:!0});null!==c&&void 0!==c&&(d.detail=c);b=new CustomEvent(b,d);a.dispatchEvent(b)}
;function xw(a,b){b=new tw(b);ww(a,"yt-action",b);return b.returnValue}
function yw(a,b,c,d){b&&b.length&&b.forEach(function(e){var f=vw(e,"action")||vw(e,"command")||vw(e,"endpoint");if(f){var g="yt"+f;var h=uw.get(g);h?g=h:(f="yt-"+f.replace(/([A-Z])/g,"-$1").toLowerCase(),uw.set(g,f),g=f);U(e,vk)&&(g+="-"+U(e,vk).signal.toLowerCase().replace(/_/g,"-"))}else g=null;g&&(S("handle_service_request_actions")&&e.commandMetadata&&e.commandMetadata.webCommandMetadata&&e.commandMetadata.webCommandMetadata.sendPost?zw(c?c:a,[e]):xw(a,[e,c,d]))})}
function zw(a,b){var c=[a];b&&c.push.apply(c,b);b=xw(a,c);return 0<b.length&&(b=b[0],ww(a,"yt-service-request-sent",b),b&&b.ajaxPromise)?(b.ajaxPromise.then(function(d){ww(a,"yt-service-request-completed",d)},function(d){ww(a,"yt-service-request-error",{error:d,
params:c})},a),b.ajaxPromise):Wd()}
;function sv(a,b,c){b=void 0===b?{}:b;var d,e=null==(d=U(a.commandMetadata,wk))?void 0:d.url;d=b.form||{};!c||d.element||d.skipDefaultElement||(b.form=b.form||{},b.form.element=c);if(e&&"/service_ajax"!==e)return{type:0,command:a,form:b.form};if(S("kevlar_service_command_check")){if(c=jr().resolve(Yu),vt(a,c.j))return Object.assign({},{type:1,command:a},b)}else{var f;if(null==(f=U(a.commandMetadata,wk))?0:f.apiUrl)return Object.assign({},{type:1,command:a},b)}return{type:2,command:a,form:b.form}}
function qv(a){if(a.form){var b=a.form,c=Object.assign({},b);b=b.element;c=(delete c.element,c);if(b)return[zw(b,[a.command,c,a.yc])]}return[]}
function rv(a){if(a.form){var b=a.form,c=Object.assign({},b);b=b.element;c=(delete c.element,c);b&&yw(b,[a.command],b,c)}}
;function Aw(a,b,c){G.call(this);var d=this;c=c||R("POST_MESSAGE_ORIGIN")||window.document.location.protocol+"//"+window.document.location.hostname;this.i=b||null;this.targetOrigin="*";this.j=c;this.sessionId=null;this.channel="widget";this.D=!!a;this.s=function(e){a:if(!("*"!=d.j&&e.origin!=d.j||d.i&&e.source!=d.i||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.D&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.j=d.targetOrigin=e.origin);d.i=e.source;d.sessionId=f.id;d.h&&(d.h(),d.h=null);break;case "command":d.l&&(!d.m||0<=cb(d.m,f.func))&&d.l(f.func,f.args,e.origin)}}};
this.m=this.h=this.l=null;window.addEventListener("message",this.s)}
w(Aw,G);Aw.prototype.sendMessage=function(a,b){if(b=b||this.i){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){Uk(d)}}};
Aw.prototype.M=function(){window.removeEventListener("message",this.s);G.prototype.M.call(this)};function Bw(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new Aw(!!R("WIDGET_ID_ENFORCE")),b=this.Je.bind(this);a.l=b;a.m=null;this.h.channel="widget";if(a=R("WIDGET_ID"))this.h.sessionId=a}
m=Bw.prototype;m.Je=function(a,b,c){"addEventListener"===a&&b?this.Jc(b[0],c):this.Zc(a,b,c)};
m.Zc=function(){};
m.Dc=function(a){var b=this;return function(c){return b.sendMessage(a,c)}};
m.Jc=function(a,b){this.j[a]||"onReady"===a||(this.addEventListener(a,this.Dc(a,b)),this.j[a]=!0)};
m.addEventListener=function(){};
m.ke=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.Gc());this.sendMessage("onReady");db(this.i,this.Fd,this);this.i=[]};
m.Gc=function(){return null};
function Cw(a,b){a.sendMessage("infoDelivery",b)}
m.Fd=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
m.sendMessage=function(a,b){this.Fd({event:a,info:void 0===b?null:b})};
m.dispose=function(){this.h=null};var Dw={},Ew=(Dw["api.invalidparam"]=2,Dw.auth=150,Dw["drm.auth"]=150,Dw["heartbeat.net"]=150,Dw["heartbeat.servererror"]=150,Dw["heartbeat.stop"]=150,Dw["html5.unsupportedads"]=5,Dw["fmt.noneavailable"]=5,Dw["fmt.decode"]=5,Dw["fmt.unplayable"]=5,Dw["html5.missingapi"]=5,Dw["html5.unsupportedlive"]=5,Dw["drm.unavailable"]=5,Dw["mrm.blocked"]=151,Dw);var Fw=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function Gw(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function Hw(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=v(Fw);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function Iw(a,b,c,d){if(Oa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function Jw(a){Bw.call(this);this.listeners=[];this.l=!1;this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.Ve.bind(this));this.addEventListener("onVolumeChange",this.We.bind(this));this.addEventListener("onApiChange",this.Qe.bind(this));this.addEventListener("onPlaybackQualityChange",this.Se.bind(this));this.addEventListener("onPlaybackRateChange",this.Te.bind(this));this.addEventListener("onStateChange",this.Ue.bind(this));this.addEventListener("onWebglSettingsChanged",
this.Xe.bind(this))}
w(Jw,Bw);m=Jw.prototype;
m.Zc=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&Gw(a)){var d=b;if(Oa(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=Hw(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=Hw(e);break;case "loadPlaylist":case "cuePlaylist":e=Iw(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);Gw(a)&&Cw(this,this.Gc())}};
m.Jc=function(a,b){"onReady"===a?this.api.logApiCall(a+" invocation",b):"onError"===a&&this.l&&(this.api.logApiCall(a+" invocation",b,this.errorCode),this.errorCode=void 0);this.api.logApiCall(a+" registration",b);Bw.prototype.Jc.call(this,a,b)};
m.Dc=function(a,b){var c=this,d=Bw.prototype.Dc.call(this,a,b);return function(e){"onError"===a?c.api.logApiCall(a+" invocation",b,e):c.api.logApiCall(a+" invocation",b);d(e)}};
m.onReady=function(){var a=this.ke.bind(this);this.h.h=a;a=this.api.getVideoData();if(!a.isPlayable){this.l=!0;a=a.errorCode;var b=void 0===b?5:b;this.errorCode=a?Ew[a]||b:b;this.sendMessage("onError",this.errorCode.toString())}};
m.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
m.Gc=function(){if(!this.api)return null;var a=this.api.getApiInterface();ib(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
m.Ue=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());Cw(this,a)};
m.Se=function(a){Cw(this,{playbackQuality:a})};
m.Te=function(a){Cw(this,{playbackRate:a})};
m.Qe=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);a.join(", ");b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
m.We=function(){Cw(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
m.Ve=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());Cw(this,a)};
m.Xe=function(){var a={sphericalProperties:this.api.getSphericalProperties()};Cw(this,a)};
m.dispose=function(){Bw.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function Kw(a){G.call(this);this.h={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.Bd,this)}
w(Kw,G);m=Kw.prototype;m.start=function(){this.started||this.Z()||(this.started=!0,this.connection.lb("RECEIVING"))};
m.lb=function(a,b){this.started&&!this.Z()&&this.connection.lb(a,b)};
m.Bd=function(a,b,c){if(this.started&&!this.Z()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=Lw(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=Mw(a,c))&&this.lb(a,c))}}};
m.addListener=function(a){if(!(a in this.h)){var b=this.Re.bind(this,a);this.h[a]=b;this.addEventListener(a,b)}};
m.Re=function(a,b){this.started&&!this.Z()&&this.connection.lb(a,this.Fc(a,b))};
m.Fc=function(a,b){if(null!=b)return{value:b}};
m.removeListener=function(a){a in this.h&&(this.removeEventListener(a,this.h[a]),delete this.h[a])};
m.M=function(){this.connection.unsubscribe("command",this.Bd,this);this.connection=null;for(var a in this.h)this.h.hasOwnProperty(a)&&this.removeListener(a);G.prototype.M.call(this)};function Nw(a,b){Kw.call(this,b);this.api=a;this.start()}
w(Nw,Kw);Nw.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
Nw.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function Lw(a,b){switch(a){case "loadVideoById":return a=Hw(b),[a];case "cueVideoById":return a=Hw(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=Iw(b),[a];case "cuePlaylist":return a=Iw(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Mw(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Nw.prototype.Fc=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Kw.prototype.Fc.call(this,a,b)};
Nw.prototype.M=function(){Kw.prototype.M.call(this);delete this.api};function Ow(a){a=void 0===a?!1:a;G.call(this);this.h=new L(a);xc(this,this.h)}
Xa(Ow,G);Ow.prototype.subscribe=function(a,b,c){return this.Z()?0:this.h.subscribe(a,b,c)};
Ow.prototype.unsubscribe=function(a,b,c){return this.Z()?!1:this.h.unsubscribe(a,b,c)};
Ow.prototype.l=function(a,b){this.Z()||this.h.ab.apply(this.h,arguments)};function Pw(a,b,c){Ow.call(this);this.j=a;this.i=b;this.id=c}
w(Pw,Ow);Pw.prototype.lb=function(a,b){this.Z()||this.j.lb(this.i,this.id,a,b)};
Pw.prototype.M=function(){this.i=this.j=null;Ow.prototype.M.call(this)};function Qw(a,b,c){G.call(this);this.h=a;this.origin=c;this.i=Hq(window,"message",this.j.bind(this));this.connection=new Pw(this,a,b);xc(this,this.connection)}
w(Qw,G);Qw.prototype.lb=function(a,b,c,d){this.Z()||a!==this.h||(a={id:b,command:c},d&&(a.data=d),this.h.postMessage(JSON.stringify(a),this.origin))};
Qw.prototype.j=function(a){if(!this.Z()&&a.origin===this.origin){var b=a.data;if("string"===typeof b){try{b=JSON.parse(b)}catch(d){return}if(b.command){var c=this.connection;c.Z()||c.l("command",b.command,b.data,a.origin)}}}};
Qw.prototype.M=function(){Iq(this.i);this.h=null;G.prototype.M.call(this)};function Rw(){this.state=1;this.h=null}
m=Rw.prototype;m.initialize=function(a,b,c){if(a.program){var d,e=null!=(d=a.interpreterUrl)?d:null;if(a.interpreterSafeScript){d=a.interpreterSafeScript.privateDoNotAccessOrElseSafeScriptWrappedValue||"";var f=wb();d=f?f.createScript(d):d;d=new Bb(d,Ab)}else d=null!=(f=a.interpreterScript)?f:null;a.interpreterSafeUrl&&(e=a.interpreterSafeUrl,yb("From proto message. b/166824318"),e=Fb(e.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||"").toString());Sw(this,d,e,a.program,b,c)}else ws(Error("Cannot initialize botguard without program"))};
function Sw(a,b,c,d,e,f){var g=void 0===g?"trayride":g;c?(a.state=2,Nv(c,function(){window[g]?Tw(a,d,g,e):(a.state=3,Sv(c),ws(new km("Unable to load Botguard","from "+c)))},f)):b?(f=Dd("SCRIPT"),b instanceof Bb?(b instanceof Bb&&b.constructor===Bb?b=b.h:(Ma(b),b="type_error:SafeScript"),f.textContent=b,Sh(f)):f.textContent=b,f.nonce=Xb(),document.head.appendChild(f),document.head.removeChild(f),window[g]?Tw(a,d,g,e):(a.state=4,ws(new km("Unable to load Botguard from JS")))):ws(new km("Unable to load VM; no url or JS provided"))}
function Tw(a,b,c,d){a.state=5;try{var e=new Eh({program:b,oe:c,Ke:S("att_web_record_metrics")});e.Ze.then(function(){a.state=6;d&&d(b)});
a.Uc(e)}catch(f){a.state=7,f instanceof Error&&ws(f)}}
m.invoke=function(a){a=void 0===a?{}:a;return this.Xc()?this.Od({kd:a}):null};
m.dispose=function(){this.Uc(null);this.state=8};
m.Xc=function(){return!!this.h};
m.Od=function(a){return this.h.Id(a)};
m.Uc=function(a){vc(this.h);this.h=a};function Uw(){var a=E("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function Vw(){Rw.apply(this,arguments)}
w(Vw,Rw);Vw.prototype.Uc=function(a){var b;null==(b=Uw())||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.Id.bind(a)},D("yt.abuse.playerAttLoader",b),D("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(D("yt.abuse.playerAttLoader",null),D("yt.abuse.playerAttLoaderRun",null))};
Vw.prototype.Xc=function(){return!!Uw()};
Vw.prototype.Od=function(a){return Uw().bgvmc(a)};var Ww=new Vw;function Xw(){return Ww.Xc()}
function Yw(a){a=void 0===a?{}:a;return Ww.invoke(a)}
;function Zw(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||rb(b);this.assets=a.assets||{};this.attrs=a.attrs||rb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Zw.prototype.clone=function(){var a=new Zw,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Ma(c)?a[b]=rb(c):a[b]=c}return a};var $w=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function ax(a){a=a||"";if(window.spf){var b=a.match($w);spf.style.load(a,b?b[1]:"",void 0)}else bx(a)}
function bx(a){var b=cx(a),c=document.getElementById(b),d=c&&Jv(c,"loaded");d||c&&!d||(c=dx(a,b,function(){if(!Jv(c,"loaded")){Hv(c);$q(b);var e=Va(ar,b);ml(e,0)}}))}
function dx(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=ok(a);Rh(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function cx(a){var b=Dd("A");Jh(b,new Hb(a,Ib));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+Zb(a)}
;function ex(){G.call(this);this.h=[]}
w(ex,G);ex.prototype.M=function(){for(;this.h.length;){var a=this.h.pop();a.target.removeEventListener(a.name,a.callback,void 0)}G.prototype.M.call(this)};function fx(){ex.apply(this,arguments)}
w(fx,ex);function gx(a,b,c,d,e){G.call(this);var f=this;this.s=b;this.webPlayerContextConfig=d;this.wc=e;this.Ba=!1;this.api={};this.ea=this.m=null;this.S=new L;this.h={};this.Y=this.ma=this.elementId=this.Ja=this.config=null;this.W=!1;this.j=this.D=null;this.na={};this.xc=["onReady"];this.lastError=null;this.qb=NaN;this.R={};this.Td=new fx(this);this.da=0;this.i=this.l=a;xc(this,this.S);hx(this);ix(this);xc(this,this.Td);c?this.da=ml(function(){f.loadNewVideoConfig(c)},0):d&&(jx(this),kx(this))}
w(gx,G);m=gx.prototype;m.getId=function(){return this.s};
m.loadNewVideoConfig=function(a){if(!this.Z()){this.da&&(window.clearTimeout(this.da),this.da=0);var b=a||{};b instanceof Zw||(b=new Zw(b));this.config=b;this.setConfig(a);kx(this);this.isReady()&&lx(this)}};
function jx(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;"video-player"===a.elementId&&(a.elementId=a.s,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.s:a.config.attrs.id=a.s);var c;(null==(c=a.i)?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
m.setConfig=function(a){this.Ja=a;this.config=mx(a);jx(this);if(!this.ma){var b;this.ma=nx(this,(null==(b=this.config.args)?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null==(c=this.config)?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.i&&(this.i.style.width=hi(Number(b)||b)),(a=a.height)&&this.i&&(this.i.style.height=hi(Number(a)||a))};
function lx(a){if(a.config&&!0!==a.config.loaded)if(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay){var b;a.api.loadVideoByPlayerVars(null!=(b=a.config.args)?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function ox(a){var b=!0,c=px(a);c&&a.config&&(a=qx(a),b=Jv(c,"version")===a);return b&&!!E("yt.player.Application.create")}
function kx(a){if(!a.Z()&&!a.W){var b=ox(a);if(b&&"html5"===(px(a)?"html5":null))a.Y="html5",a.isReady()||rx(a);else if(sx(a),a.Y="html5",b&&a.j&&a.l)a.l.appendChild(a.j),rx(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.D=function(){c=!0;var d=tx(a,"player_bootstrap_method")?E("yt.player.Application.createAlternate")||E("yt.player.Application.create"):E("yt.player.Application.create");var e=a.config?mx(a.config):void 0;d&&d(a.l,e,a.webPlayerContextConfig,a.wc);rx(a)};
a.W=!0;b?a.D():(Nv(qx(a),a.D),(b=ux(a))&&ax(b),vx(a)&&!c&&D("yt.player.Application.create",null))}}}
function px(a){var b=Cd(a.elementId);!b&&a.i&&a.i.querySelector&&(b=a.i.querySelector("#"+a.elementId));return b}
function rx(a){if(!a.Z()){var b=px(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.W=!1;if(!tx(a,"html5_remove_not_servable_check_killswitch")){var d;if((null==b?0:b.isNotServable)&&a.config&&(null==b?0:b.isNotServable(null==(d=a.config.args)?void 0:d.video_id)))return}wx(a)}else a.qb=ml(function(){rx(a)},50)}}
function wx(a){hx(a);a.Ba=!0;var b=px(a);if(b){a.m=xx(a,b,"addEventListener");a.ea=xx(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=xx(a,b,f))}}for(var g in a.h)a.h.hasOwnProperty(g)&&a.m&&a.m(g,a.h[g]);lx(a);a.ma&&a.ma(a.api);a.S.ab("onReady",a.api)}
function xx(a,b,c){var d=b[c];return function(){var e=B.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,ws(f))}}}
function hx(a){a.Ba=!1;if(a.ea)for(var b in a.h)a.h.hasOwnProperty(b)&&a.ea(b,a.h[b]);for(var c in a.R)a.R.hasOwnProperty(c)&&window.clearTimeout(Number(c));a.R={};a.m=null;a.ea=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Ja};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
m.isReady=function(){return this.Ba};
function ix(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){$q("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){$q("WATCH_LATER_VIDEO_REMOVED",b)})}
m.addEventListener=function(a,b){var c=this,d=nx(this,b);d&&(0<=cb(this.xc,a)||this.h[a]||(b=yx(this,a),this.m&&this.m(a,b)),this.S.subscribe(a,d),"onReady"===a&&this.isReady()&&ml(function(){d(c.api)},0))};
m.removeEventListener=function(a,b){this.Z()||(b=nx(this,b))&&this.S.unsubscribe(a,b)};
function nx(a,b){var c=b;if("string"===typeof b){if(a.na[b])return a.na[b];c=function(){var d=B.apply(0,arguments),e=E(b);if(e)try{e.apply(C,d)}catch(f){vs(f)}};
a.na[b]=c}return c?c:null}
function yx(a,b){var c="ytPlayer"+b+a.s;a.h[b]=c;C[c]=function(d){var e=ml(function(){if(!a.Z()){try{a.S.ab(b,null!=d?d:void 0)}catch(h){ws(new km("PlayerProxy error when creating global callback",{error:h,event:b,playerId:a.s,data:d}))}var f=a.R,g=String(e);g in f&&delete f[g]}},0);
ob(a.R,String(e))};
return c}
m.getPlayerType=function(){return this.Y||(px(this)?"html5":null)};
m.getLastError=function(){return this.lastError};
function sx(a){a.cancel();hx(a);a.Y=null;a.config&&(a.config.loaded=!1);var b=px(a);b&&(ox(a)||!vx(a)?a.j=b:(b&&b.destroy&&b.destroy(),a.j=null));if(a.l)for(a=a.l;b=a.firstChild;)a.removeChild(b)}
m.cancel=function(){this.D&&Tv(qx(this),this.D);window.clearTimeout(this.qb);this.W=!1};
m.M=function(){sx(this);if(this.j&&this.config&&this.j.destroy)try{this.j.destroy()}catch(b){vs(b)}this.na=null;for(var a in this.h)this.h.hasOwnProperty(a)&&(C[this.h[a]]=null);this.Ja=this.config=this.api=null;delete this.l;delete this.i;G.prototype.M.call(this)};
function vx(a){var b,c;a=null==(b=a.config)?void 0:null==(c=b.args)?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function qx(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function ux(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function tx(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if(null==(d=a.config)?0:d.args)c=a.config.args.fflags}return"true"===Xk(c||"","&")[b]}
function mx(a){for(var b={},c=v(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?rb(e):e}return b}
;var zx={},Ax="player_uid_"+(1E9*Math.random()>>>0);function Bx(a,b){var c="player",d=!1;d=void 0===d?!0:d;c="string"===typeof c?Cd(c):c;var e=Ax+"_"+Pa(c),f=zx[e];if(f&&d)return Cx(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new gx(c,e,a,b,void 0);zx[e]=f;$q("player-added",f.api);yc(f,function(){delete zx[f.getId()]});
return f.api}
function Cx(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var Dx=null,Ex=null,Fx=null;function Gx(){Hx()}
function Ix(){Hx()}
function Hx(){var a=Dx.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function pv(a){var b,c;if(a=null==(b=a.command)?void 0:null==(c=b.urlEndpoint)?void 0:c.url)b=window,c=Ih(a),void 0!==c&&b.open(c,void 0,void 0);return[]}
function Jx(){Dx&&Dx.sendAbandonmentPing&&Dx.sendAbandonmentPing();R("PL_ATT")&&Ww.dispose();for(var a=pi,b=0,c=Uv.length;b<c;b++)a.qa(Uv[b]);Uv.length=0;Sv("//static.doubleclick.net/instream/ad_status.js");Vv=!1;Ok("DCLKSTAT",0);wc(Fx,Ex);Dx&&(Dx.removeEventListener("onVideoDataChange",Gx),Dx.destroy())}
;function Kx(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=R("EVENT_ID");d&&(b.ei||(b.ei=d));b&&Ht(a,b);if(c)return!1;Pt(a);if((window.ytspf||{}).enabled)spf.navigate(a);else{var e=void 0===e?{}:e;var f=void 0===f?"":f;var g=void 0===g?window:g;a=lc(a,e);Pt(a);f=a+f;var h=void 0===h?ai:h;a:{h=void 0===h?ai:h;for(a=0;a<h.length;++a)if(b=h[a],b instanceof Zh&&b.ye(f)){h=new Hb(f,Ib);break a}h=void 0}g=g.location;h=Ih(h||Jb);void 0!==h&&(g.href=h)}return!0}
;D("yt.setConfig",Ok);D("yt.config.set",Ok);D("yt.setMsg",Rs);D("yt.msgs.set",Rs);D("yt.logging.errors.log",vs);
D("writeEmbed",function(){var a=R("PLAYER_CONFIG");if(!a){var b=R("PLAYER_VARS");b&&(a={args:b})}kt(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=R("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);Ju("embed",["ol"]);c=R("WEB_PLAYER_CONTEXT_CONFIGS").WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=bl(window.location.href);
d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}var e;(null==(e=a.args)?0:e.autoplay)&&Ju("watch",["pbs","pbu","pbp"]);Dx=Bx(a,c);S("embeds_enable_server_driven_watch_again_on_youtube")&&!ov.h&&(ov.h=new ov);Dx.addEventListener("onVideoDataChange",Gx);Dx.addEventListener("onReady",Ix);S("embeds_enable_server_driven_watch_again_on_youtube")&&Dx.addEventListener("innertubeCommand",function(f){tv(ov.h,f)});
a=R("POST_MESSAGE_ID","player");R("ENABLE_JS_API")?Fx=new Jw(Dx):R("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(Ex=new Qw(window.parent,a,b),Fx=new Nw(Dx,Ex.connection));Wv();S("ytidb_create_logger_embed_killswitch")||an();a={};nw.h||(nw.h=new nw);nw.h.install((a.flush_logs={callback:function(){$r()}},a));
xq();S("ytidb_clear_embedded_player")&&pi.oa(function(){var f,g;if(!nv){var h=jr(),k={Rc:mv,Md:lv};h.h.set(k.Rc,k);k={zc:{feedbackEndpoint:xt(gv),modifyChannelNotificationPreferenceEndpoint:xt(hv),playlistEditEndpoint:xt(iv),subscribeEndpoint:xt(ev),unsubscribeEndpoint:xt(fv),webPlayerShareEntityServiceEndpoint:xt(jv)}};var l=ut(),n={};l&&(n.client_location=l);void 0===f&&(f=Pl());void 0===g&&(g=h.resolve(mv));Su(k,g,f,n);f={Rc:Yu,Nd:Ru.h};h.h.set(f.Rc,f);nv=h.resolve(Yu)}Gv()})});
var Lx=Sk(function(){Nu();lt()}),Mx=Sk(function(a){a.persisted||(Nu(),lt())}),Nx=Sk(function(a){S("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?Jx():a.persisted||Jx()}),Ox=Sk(Jx);
window.addEventListener?(window.addEventListener("load",Lx),window.addEventListener("pageshow",Mx),window.addEventListener("pagehide",Nx)):window.attachEvent&&(window.attachEvent("onload",Lx),window.attachEvent("onunload",Ox));
window.onerror=function(a,b,c,d,e){b=void 0===b?"Unknown file":b;c=void 0===c?0:c;var f=!1,g=Pk("log_window_onerror_fraction");if(g&&Math.random()<g)f=!0;else{g=document.getElementsByTagName("script");for(var h=0,k=g.length;h<k;h++)if(0<g[h].src.indexOf("/debug-")){f=!0;break}}f&&(f=!1,e?f=!0:("string"===typeof a?g=a:ErrorEvent&&a instanceof ErrorEvent?(f=!0,g=a.message,b=a.filename,c=a.lineno,d=a.colno):(g="Unknown error",b="Unknown file",c=0),e=new km(g),e.name="UnhandledWindowError",e.message=
g,e.fileName=b,e.lineNumber=c,isNaN(d)?delete e.columnNumber:e.columnNumber=d),f?vs(e):ws(e))};
ke=xs;window.addEventListener("unhandledrejection",function(a){xs(a.reason)});
db(R("ERRORS")||[],function(a){vs.apply(null,a)});
Ok("ERRORS",[]);D("yt.abuse.player.botguardInitialized",E("yt.abuse.player.botguardInitialized")||Xw);D("yt.abuse.player.invokeBotguard",E("yt.abuse.player.invokeBotguard")||Yw);D("yt.abuse.dclkstatus.checkDclkStatus",E("yt.abuse.dclkstatus.checkDclkStatus")||Xv);D("yt.player.exports.navigate",E("yt.player.exports.navigate")||Kx);D("yt.util.activity.init",E("yt.util.activity.init")||Mq);D("yt.util.activity.getTimeSinceActive",E("yt.util.activity.getTimeSinceActive")||Sq);
D("yt.util.activity.setTimestamp",E("yt.util.activity.setTimestamp")||Nq);}).call(this);
