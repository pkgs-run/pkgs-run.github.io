{{ range os.ReadDir "." }}
  {{ .Name }}
{{ end }}
