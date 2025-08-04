# My Expenses

| Date | Category | Description | Amount |
|------|----------|-------------|--------|
{{ range .Site.Data.expenses }}| {{ .date }} | {{ .category }} | {{ .description }} | ${{ .amount }} |
{{ end }}