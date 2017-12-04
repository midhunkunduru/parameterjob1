properties([
  parameters([
    string(name: 'Version', description: 'Possible options: 1 1.1 1.2 1.3', defaultValue: ''),
    string(name: 'Application', description: 'Possible options: .net java', defaultValue: ''),
   
  ])
])
node("master")
{
  def a = "somevalue"
    stage("Checkout")
{
  echo "${a}"
  echo "${Version}"
  
  echo "${Application}"
  
    
}
    
    stage("Build")
    {
        echo "Sample build"
    }

}
