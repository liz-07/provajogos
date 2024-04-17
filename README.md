*4.3.4 Estimativa de máxima verossimilhança**

Para estimar os parâmetros do modelo, adaptamos um algoritmo proposto por Anderson (1973). A log-verossimilhança para o modelo especial linear t-Student é dado por

$L(\theta)=log(K_{n}(\eta))-\frac{1}{2}log|\Sigma|-\frac{1}{2n}(1+{n}\eta)log)+c(\eta)\delta)$ 
        
**com** $log(K_{n}(\eta))=\frac{n}{2}log(\frac{c(\eta)}{\Pi})+log\Gamma(\frac{1+{n}\eta}{2\eta}), \delta=(\boldsymbol{Y} - \boldsymbol{X}\beta)^T\Sigma^{-1}(\boldsymbol{Y} - \boldsymbol{X}\beta)$ **e** $c(\eta)=(\eta)=(\eta)(1 - 2(\eta), 0 < (\eta) < \frac{1}{2}. **Conforme observado por Zellner (1976), a função log-verossimilhança (4.4) é uma função decrescente de (\eta), e então não pode ser estimado por máximo verossimilhança. Veja também De Bastiani et al. (2015)**$
