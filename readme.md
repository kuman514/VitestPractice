# VitestPractice

Vitest를 이용한 테스트 라이브러리를 효과적으로 적용해보기 위해 집중적으로 연마하는 레포지토리.

## 연습할 항목

- 기본 구조
  - describe
  - it
  - beforeEach
  - afterEach
  - beforeAll
  - afterAll
- 모킹
  - vi.fn()
  - vi.spyOn()
  - vi.mock()
  - vi.unmock()
  - vi.clearAllMocks()
  - vi.resetAllMocks()
  - vi.restoreAllMocks()
- expect
  - expect.toThrow()
  - expect.toHaveBeenCalledWith()
  - expect.toMatchObject()
  - expect.toBeCloseTo()
  - expect.toMatchSnapshot()
  - expect.toMatchInlineSnapshot()
  - expectTypeOf()
- 목타이머 (setInterval, setTimeout 제어)
  - vi.useFakeTimers()
  - vi.runAllTimers()
  - vi.advanceTimersByTime()
- 커버리지
  - `--coverage`
- 벤치마킹
  - bench
  - describeBench
