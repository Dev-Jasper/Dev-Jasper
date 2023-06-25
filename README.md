# Hey, I'm HyunSang 👋🏻
- Software Engineer🧑🏻‍💻 **[@TeamGRIT, Inc.](https://teamgrit.kr) Back-End Development Team**
- Community Organizer **[@GDG(Google Developers Group) Golang Korea](https://gdg.community.dev/gdg-golang-korea/)**
- Undergraduate Student **[@Soonchunhyang University](https://home.sch.ac.kr/security/index.jsp) Department Information Security Engineering Major**

```go
type HyunSangInfo struct {
	Name       string
	Email      string
	Blog       string
	Company    string
	University string
	Community  string
	TechStack  map[string]string
}

func (info *HyunSangInfo) NewHyunSang() *HyunSangInfo {
	info.Name = "HyunSang Park"
	info.Email = "me@hyunsang.dev"
	info.Blog = "https://hyunsang.dev"
	info.Company = "Back-End Software Engineer @TeamGRIT, Inc."
	info.University = "Undergraduate Student @SCH Univ Dept. Information Security"
	info.Community = "Community Organizer @GDG Golang Korea"
	info.TechStack = map[string]string{
		"Language": "Golang, Rust 🦀, JavaScript(Vue.js)",
		"Database": "MySQL, MongoDB, SQLite, Redis",
		"Cloud":    "Amazon Web Services, Azure, Naver Cloud Platform",
		"CI/CD":    "GitHub Actions, Docker",
		"Tools": "Slack, Google Docs, Notion"
	}

	return info
}
```
