# 개요
* code-serve을 쿠버네티스에 배포 연습
* 유투브 영상: https://youtu.be/27vM4Wa97ow

# 실행방법
* ingress host수정
* 배포
```sh
kubectl apply -f ./manifests/
```

# 삭제방법
```sh
kubectl delete -f ./manifests/
```

# 참고자료
* https://www.digitalocean.com/community/tutorials/how-to-set-up-the-code-server-cloud-ide-platform-on-digitalocean-kubernetes
