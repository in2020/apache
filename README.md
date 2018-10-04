# apache
## Tips
### 크로스도메인 허용
- 참조 (http://adrenal.tistory.com/16)
```
Header set Access-Control-Allow-Origin "*" #전체 허용  
```
### MPM(Multi-Processing Module)
- (https://httpd.apache.org/docs/2.4/ko/mpm.html)
- (https://httpd.apache.org/docs/2.4/ko/mod/)
- (https://httpd.apache.org/docs/2.4/ko/misc/perf-tuning.html) : 여러 시스템에서 prefork의 속도는 worker와 비슷하지만..
- 동시사용자가 많을때 event 모드 사용이 유리. 속도 차이가 아니라 resource 사용 면에서 효율적인 것으로 보인다... 
