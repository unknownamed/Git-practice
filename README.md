<a id="project-overview-added"></a>

[프로젝트 안내](#project-overview-added) · [기존 README 전체 내용](#original-readme-preserved)

# Git Command Practice

**Git 명령어를 직접 사용하며 역할과 작업 흐름을 정리한 실습 저장소입니다.**

명령어별 기록을 아래에서 바로 찾아볼 수 있습니다.

## 실습 목차

| 명령어 | 학습 내용 | 기록 |
| --- | --- | --- |
| ADD | 변경 사항을 스테이징에 올리기 | [README_ADD.md](README_ADD.md) |
| COMMIT | 선택한 변경을 커밋으로 기록 | [README_COMMIT.md](README_COMMIT.md) |
| PUSH | 로컬 커밋을 원격 저장소로 공유 | [README_PUSH.md](README_PUSH.md) |
| MERGE | 브랜치 변경을 합치기 | [README_MERGE.md](README_MERGE.md) |
| RESET | HEAD·인덱스·작업 트리 변경 이해 | [README_RESET.md](README_RESET.md) |
| TAG | 특정 커밋에 버전 표시 | [README_TAG.md](README_TAG.md) |
| REVERT | 이전 변경을 되돌리는 커밋 만들기 | [README_REVERT.md](README_REVERT.md) |

RESET 문서는 짧은 초기 메모이며, 옵션별 예시는 아직 정리되지 않았습니다.

## 기본 흐름

```text
파일 수정 → git add → git commit → git push
```

```bash
git status
git diff
git log --oneline --graph
```

이 저장소는 실행 애플리케이션이 아닌 학습 기록입니다. [Git·GitHub 개념 가이드](https://github.com/unknownamed/Git-GitHub-Quick-Reference-Guide)와 함께 볼 수 있습니다.

---

<a id="original-readme-preserved"></a>

## 기존 README 전체 내용

# GIT 명령어 실습
- (완료) ADD
- (완료) COMMIT
- (완료) PUSH
- (완료) MERGE
- RESET
- (완료) TAG
- (완료) REVERT
