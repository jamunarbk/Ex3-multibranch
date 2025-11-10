pipeline { 
agent any 
environment { 
VERSION = "1.0-feature-login" // you can change per-branch, e.g., "1.0-dev" 
} 
stages { 
stage('ShowVersion') { 
steps { 
echo "Current version is ${env.VERSION}" 
} 
} 
} 
}
