pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo "branch yow"
            }
        }
        stage('donkey') {
        	steps{
        		echo "branch donkeytime!"
        	}
        }
    }
    post {
    	always{
    		echo "so guys we did it"
    	}
    	changed{
    		echo "I'm, I'm just amazed"
    	}
    	success{
    		echo "we reached a quarter of a million subscribers"
    	}
    	failure{
    		echo "two hundred and fifty thousand and still growing"
    	}
    	unstable{
    		echo "the fact that we've reached this number in such a short amount of time is just phenomenal"
    	}
    }
}