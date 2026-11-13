# NM-dev-ex14
# Ex14 – Static Program Analysis using SonarLint

Completed

Objective: Perform static program analysis during coding using the SonarLint plugin in Eclipse IDE.

### Step-by-step procedure

Step 1: Open Eclipse

1. Open Eclipse IDE.
2. Select the existing workspace.
3. Open the existing Calculator project.
4. Navigate to `src/main/java`.
5. Open `Calculator.java`.

Step 2: Install SonarLint

1. Go to Help → Eclipse Marketplace.
2. Search for `SonarQube for IDE`.
3. Click Install.
4. Accept the licence agreement.
5. Wait for the installation to complete.
6. Restart Eclipse when prompted.

Step 3: Open SonarLint On-the-fly

1. Go to Window → Show View → Other.
2. Expand SonarLint.
3. Select SonarLint On-the-fly.
4. Click Open.

Step 4: Add sample code to generate issues

Add the following method inside the Calculator class:

```
public void calculate(int a) {
    System.out.println(a);
}
```

1. Save the file using `Ctrl + S`.
2. Wait for SonarLint to analyse the code.

Step 5: Identify code quality issues

SonarLint detected these two issues:

1. Replace this use of System.out by a logger.
2. Move this file to a named package.

Step 6: Open SonarLint Rule Description

1. Go to Window → Show View → Other.
2. Expand SonarLint.
3. Select SonarLint Rule Description.
4. Click Open.

Step 7: View rule explanations

1. Return to the SonarLint On-the-fly tab.
2. Select any detected issue.
3. Switch to the SonarLint Rule Description tab.
4. View the explanation and suggested correction.

### Result

Successfully installed SonarLint in Eclipse, performed static code analysis on the Calculator project, identified two code quality issues, and viewed their rule descriptions and suggested corrections.

Conclusion: Learned how to perform static program analysis using SonarLint during coding.

Ex14 Completed
