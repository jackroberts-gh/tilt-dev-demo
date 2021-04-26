docker_build('example-html-image', '.')
k8s_yaml('app.yaml')
k8s_resource('example-html', port_forwards=8001)