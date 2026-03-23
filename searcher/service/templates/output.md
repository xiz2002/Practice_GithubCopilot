## **Domain Searcher (Service)**: `{{domain_path}}` 분석 결과

### [처리 흐름]

#### {{오퍼레이션 명}}
```
{{ControllerClass}}.{{method}}()
  → (분기 조건: {{typeCode=A 등}})
  → {{ServiceClass}}.{{method}}()
    → {{RepositoryClass / MapperClass}}.{{method}}()
```

### [외부 연동 흐름] *(해당하는 경우)*
#### {{오퍼레이션 명}}
```
{{ServiceClass}}.{{method}}()
  → {{외부시스템 / 메시지큐}}: {{설명}}
```

---

### [처리 상세]

#### {{오퍼레이션 명}}
{{비즈니스 로직의 상세 처리 내용 서술}}

---

### [비고]
- {{레거시 코드, 미사용 파일, 기술 부채, 추가 분석 권장 영역 등}}
