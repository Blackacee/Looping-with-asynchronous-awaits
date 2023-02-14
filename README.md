# Looping-with-asynchronous-awaits
(async() => {
 data = [1, 2, 3, 4, 5];
 for (let e of data) {
 const i = await somePromiseFn(e);
 console.log(i);
 }
 console.log('this will print last');
})();
