---
layout: post
title: "Function Homework"
date: 2021-11-22
excerpt: "Python Grammar"
tags: [sample post, readability, test]
comments: true
---

# Function Homework

- 함수의 인자로 시작과 끝 숫자를 받아 시작부터 끝까지의 모든 정수값의 합을 리턴하는 함수를 작성 

   - def sum(start, end):
> Answer
>     def sum(start, end):
>     a = 0
>     while end >= start:
>            a = a + end
>            end = end-1
>            return a
>     print(sum(1,10))

- 함수의 인자로 문자열을 포함하는 리스트가 입력될 때 각 문자열의 첫 세 글자로만 구성된 리스트를 리턴하는 함수를 작성
 예를 들어, [‘Africa’, ‘Korea’, ‘China’]가 입력될 때 함수의 리턴값은 [‘Afr’, ‘Kor’, ‘Chi’]
 
   - study = ['Java', 'Python', 'DataStructure', 'Algorithm', 'BigData']
   - def first3(subject):
> Answer
> 
>     study = ['Africa', 'Korea', 'China']
>    
>     def first3(subject):
>            b = []
>            for a in subject:
>            b.append(a[0:3])
>            return b
>     print(first3(study))
