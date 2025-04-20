pipeline {
agent any

stages {
stage(&#39;Get Code&#39;) {
steps {
git url: &#39;https://github.com/usadhana/my-ne-repo.git&#39;, branch: &#39;master&#39;
}
}
stage(&#39;Build&#39;) {
steps {
echo &#39;Trying to build the project...&#39;
bat &#39;dir&#39; // List files (Windows equivalent of &#39;ls&#39;)
}
}
stage(&#39;Test&#39;) {
steps {
echo &#39;Running tests...&#39;

}
}
stage(&#39;Deploy&#39;) {
steps {
echo &#39;Deploying the application...&#39;
}
}
}
}
