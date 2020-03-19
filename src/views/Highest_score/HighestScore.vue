<template>
    <div class="main-section">
        <div class="score-section">
            <p>HIGHSCORES</p>
            <table>
                <thead>
                    <tr>
                        <td>Position</td>
                        <td>Score</td>
                        <td>Name</td>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>1st</td>
                        <td>10000000</td>
                        <td>CMK</td>
                    </tr>
                    <tr>
                        <td>2nd</td>
                        <td>1000000</td>
                        <td>KMC</td>
                    </tr>
                    
                    <tr>
                        <td>3rd</td>
                        <td>10000</td>
                        <td>RMC</td>
                    </tr>
                    
                    <tr>
                        <td>4th</td>
                        <td>1000</td>
                        <td>MMC</td>
                    </tr>
                    
                    <tr>
                        <td>5th</td>
                        <td>100</td>
                        <td>VMC</td>
                    </tr>
                    
                    <tr>
                        <td>6th</td>
                        <td>050</td>
                        <td>SMC</td>
                    </tr>
                    
                    <tr>
                        <td>7th</td>
                        <td>030</td>
                        <td>OMC</td>
                    </tr>
                </tbody>
            </table> 
        </div>
             
    </div>
</template>

<style scoped>
.score-section {
  width: 50%;
  margin: 2% auto 0;
}
.score-section p {
    text-align: center;
    font-size: 24px;
    font-weight: bold;
}
table {
  width: 100%;
  background: #ada7a7;
  cursor: pointer;
  color: blue;
}
thead td {
    font-size: 18px;
    padding: 6px 0;
}
td {
    text-align: center;
}
p {
    color: aqua;
}
</style>