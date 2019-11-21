output = ""
pipeline{
  agent any
  libraries {
    lib('lib-demo@master')
  }
  stages{
    stage('Demo'){
      steps{
	script{
	  output = name 'Mani'
	  println(output)
	}
      }
    }
  }
}
