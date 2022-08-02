# SOMA-DOS-VALORES-PARES-DAS-MATRIZES-COD-JAVA

public class MediaParesMatriz {
	public static void main(String[] args) {
		int[][] matriz = new int[2][4];
		
		for(int linha = 0; linha < matriz.length; linha++) { 
			for(int coluna = 0; coluna < matriz[linha].length; coluna++) {
				System.out.printf("matriz[%d][%d]: ", linha, coluna);
				matriz[linha][coluna] = Integer.parseInt(System.console().readLine());
			}
		}
		
		int somaPares = 0;
		[int quantPares = 0;]
		[for(int linha = 0; linha < matriz.length; linha++)] {
			[for(int coluna = 0; coluna < matriz[linha].length; coluna++)] {
				[if(matriz[linha][coluna] % 2 == 0)] {
					[somaPares += matriz[linha][coluna];]
					quantPares++;
				}
			}
		}
		
		double media = somaPares / (double) quantPares;
		
		System.out.printf("\nMEDIA DOS ELEMENTOS PARES NA MATRIZ = %.1f.\n", media);
	}
}
