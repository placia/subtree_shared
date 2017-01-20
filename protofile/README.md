# OCB Check에서 사용하는 Protocol buffer 파일을 모아둔 곳입니다.

## Directory Structure
세부 Directory 구조는 다음과 같습니다.



```
TBD

├── README.md
├── 시스템 단위 폴더 (ex. auth)
│   └── autho.proto
├── 시스템 단위 폴더 (ex. transaction)
│   └── ...

```

## 주의사항 
- 하위에 각 시스템 영역별로 별도 folder를 만들어 protocol buffer file을 관리해 주시기 바랍니다.
- `protocol buffer` 의 버전은 [proto3](https://developers.google.com/protocol-buffers/docs/proto3)를 사용해 주시기 바랍니다.
- grpc port는 50051 번으로 통일해 주시기 바랍니다.