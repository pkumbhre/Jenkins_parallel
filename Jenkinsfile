pipeline
{
    agent any
    stages{
        stage('print hi')
        {steps {sh 'echo hi'}}
        stage('Executing unit and component test')   ??common stage
        {parallel
        {stage('Execute unit test')
         {steps {sh 'echo execute_unit_test'}}
         stage('Execute component test')
         {steps{sh 'echo execute_component_test'}}
         }
        }
        
    }
}
