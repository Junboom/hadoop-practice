# Hadoop Practice

> HDFS(하둡파일시스템) + MapReduce = Hadoop

## HDFS

>> Hadoop Distributed File System
>
> 대용량 파일을 분산된 서버에 저장하고, 저장된 데이터를 빠르게 처리할 수 있게 하는 파일 시스템
> 저사양의 서버를 이용해서 스토리지를 구성할 수 있어 기존의 대용량 파일 시스템(NAS, DAS, SAN 등)에 비해 장점을 가진다.

## MapReduce

> 여러 노드에 태스크를 분배하는 방법
> 큰 작업에 대해 fork로 분할
> 텍스트 안에 단어가 몇 번 나왔는가 Map 작업을 수행, 각각의 블럭 결과 정보를 합치는 Reduce 작업을 수행


## 정리

> MapReduce 작업이 끝나면 HDFS에 파일이 써지고, MapReduce 작업이 시작할 때는 HDFS로 부터 파일을 가져오는 작업을 수행한다.
