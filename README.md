# T4_WP_SASTScan(with Semgrep CI)

- PR/Push 시 **Semgrep** 자동 실행 → GitHub Code Scanning에서 결과 확인
- (옵션) `SEMGREP_APP_TOKEN` 설정 시 Semgrep Cloud 연동

## Local
- PHP/WordPress 플러그인 개발용 스켈레톤
- Dev tools: `composer install`, `composer lint`, `composer test`

## CI
- `.github/workflows/semgrep.yml` 참고
