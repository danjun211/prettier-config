# My Prettier configuration

## 프로젝트에 통합하기

1. devDependency에 패키지를 설치

  ```sh
  # with Yarn
  $ yarn add -D @danjun211/prettier-config
  
  # with npm
  $ npm i -D @danjun211/prettier-config
  
  # with pnpm
  $ pnpm add -D @danjun211/prettier-config
  ```

1. devDependencies에 peerDendencies를 설치

  ```sh
  # with Yarn
  $ yarn dlx install-peerdeps --dev @danjun211/prettier-config
  
  # with npm
  $ npx install-peerdeps --dev @danjun211/prettier-config
  
  #with pnpm
  $ pnpm dlx install-peerdeps --dev @danjun211/prettier-config
  ```

1. 프로젝트에서 사용

프로젝트 루트 경로에 `.prettierrc` 을 생성하고, 다음 내용을 붙여넣기
  
  ```json
  "@danjun211/prettier-config"
  ```
