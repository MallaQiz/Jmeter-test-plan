# Jmeter-test-plan
org.apache.jmeter.testelement.TestPlan::class {
    props {
        it[name] = "Test Plan"
        it[guiClass] = "org.apache.jmeter.control.gui.TestPlanGui"
        it[userDefinedVariables] = org.apache.jmeter.config.Arguments().apply {
            props {
                it[name] = "User Defined Variables"
                it[guiClass] = "org.apache.jmeter.config.gui.ArgumentsPanel"
                it[testClass] = "org.apache.jmeter.config.Arguments"
            }
        }
    }
}
