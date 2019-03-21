# interview-questions
前端面试题目汇总，每日一道面试题目

# Javascript

* 1.数组的去重问题
  * i.indexof（）
`
let arr2
for(let i=0;i<arr.length;i++){
  if(arr.indexof(arr[i])===i){
  arr2[i]=arr[i]
}
}
`
  * ii.计数排序去重(只能是正整数)
`
let hash={}
for(let i=0;i<arr.length;i++){
  if(arr[i] in hash){}
  else{hash[arr[i]=true}
}
let arr2=hash.keys()//此时数组的每一项都是字符串
arr2.map(()=>{})
`
  * iii.set对象
`
let arr2=Array.from(new Set(arr))
`
* 2.去除空格
`
//api出去空格
String.trim()
//正则去除空格
function trim(string){
  return string.repalce(/^\s+|\s+$/,’’)
}
`

# Css

# Html

