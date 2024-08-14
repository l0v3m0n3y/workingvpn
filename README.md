# workingvpn
JavaScript library for workingvpn.com
# main
```js
async function main(){
    const {workingvpn} = require('./workingvpn');
    const myvpn= new workingvpn();
    let req=await myvpn.servers_list()
    console.log(req)
}
main()
```
