# embedding_cognos_nodejs



-- DB2_10_CUSFNA
SELECT 
	CUSCUN AS LLAVE, 
	CUSFNA AS VALOR,
	'CUSFNA' AS CAMPO,
	'DIPDATA.TCA003AUD' AS TABLA,
	'GTM' AS PAIS,
                'PRIMER NOMBRE' AS NOMBRE_CAMPO,
                CUSLGT AS TIPO_CLIENTE
FROM	BODSGTM.ODCUMST;


-- DB2_20_PRMNMB
SELECT 
	Concat(TC0CIF,TC0TIP) AS LLAVE, 
	PRMNMB AS VALOR,
	'PRMNMB' AS CAMPO,
	'TODSGTM.ODTCA003' AS TABLA,
	'GTM' AS PAIS,
                'PRIMER NOMBRE' AS NOMBRE_CAMPO,
                TC0TI1 AS TIPO_CLIENTE
FROM	TODSGTM.ODTCA003;

-- DB2_30_CUSFN2
SELECT 
	CUSCUN AS LLAVE, 
	CUSFN2 AS VALOR,
	'CUSFN2' AS CAMPO,
	'DIPDATA.TCA003AUD' AS TABLA,
	'GTM' AS PAIS,
                'SEGUNDO NOMBRE' AS NOMBRE_CAMPO,
                CUSLGT AS TIPO_CLIENTE	
FROM	BODSGTM.ODCUMST;


-- DB2_40_SEGNMB
SELECT 
	Concat(TC0CIF,TC0TIP) AS LLAVE, 
	SEGNMB AS VALOR,
	'SEGNMB' AS CAMPO,
	'TODSGTM.ODTCA003' AS TABLA,
	'GTM' AS PAIS,
                'PRIMER NOMBRE' AS NOMBRE_CAMPO,
                TC0TI1 AS TIPO_CLIENTE
FROM	TODSGTM.ODTCA003;


-- DB2_50_CUSLN1
SELECT 
	CUSCUN AS LLAVE, 
	CUSLN1 AS VALOR,
	'CUSLN1' AS CAMPO,
	'DIPDATA.TCA003AUD' AS TABLA,
	'GTM' AS PAIS,
                'PRIMER APELLIDO' AS NOMBRE_CAMPO,
                CUSLGT AS TIPO_CLIENTE
FROM	BODSGTM.ODCUMST;

-- DB2_60_SEGAPL

SELECT 
	Concat(TC0CIF,TC0TIP) AS LLAVE, 
	PRMAPL AS VALOR,
	'PRMAPL' AS CAMPO,
	'TODSGTM.ODTCA003' AS TABLA,
	'GTM' AS PAIS,
                'PRIMER APELLIDO' AS NOMBRE_CAMPO,
                TC0TI1 AS TIPO_CLIENTE
FROM	TODSGTM.ODTCA003;


-- DB2_70_CUSLN2

SELECT 
	CUSCUN AS LLAVE, 
	CUSLN2 AS VALOR,
	'CUSLN2' AS CAMPO,
	'DIPDATA.TCA003AUD' AS TABLA,
	'GTM' AS PAIS,
                'SEGUNDO APELLIDO' AS NOMBRE_CAMPO,
                CUSLGT AS TIPO_CLIENTE
FROM	BODSGTM.ODCUMST;


-- DB2_80_SEGAPL

SELECT 
	Concat(TC0CIF,TC0TIP) AS LLAVE, 
	SEGAPL AS VALOR,
	'SEGAPL' AS CAMPO,
	'TODSGTM.ODTCA003' AS TABLA,
	'GTM' AS PAIS,
                'SEGUNDO APELLIDO' AS NOMBRE_CAMPO,
                TC0TI1 AS TIPO_CLIENTE
FROM	TODSGTM.ODTCA003;


-- DB2_90_APLCAS
SELECT 
	Concat(TC0CIF,TC0TIP) AS LLAVE, 
	APLCAS AS VALOR,
	'APLCAS' AS CAMPO,
	'TODSGTM.ODTCA003' AS TABLA,
	'GTM' AS PAIS, 	
                'APELLIDO CASADA' AS NOMBRE_CAMPO,
                TC0TI1 AS TIPO_CLIENTE
FROM	TODSGTM.ODTCA003;


-- DB2_100_CUSNA1
SELECT 
	CUSCUN AS LLAVE, 
	CUSNA1 AS VALOR,
	'CUSNA1' AS CAMPO,
	'DIPDATA.TCA003AUD' AS TABLA,
	'GTM' AS PAIS,
                'NOMBRE COMPLETO' AS NOMBRE_CAMPO	,
                CUSLGT AS TIPO_CLIENTE
FROM	BODSGTM.ODCUMST;


-- DB2_110_TC0NOM
SELECT 
	Concat(TC0CIF,TC0TIP) AS LLAVE, 
	TC0NOM AS VALOR,
	'TC0NOM' AS CAMPO,
	'TODSGTM.ODTCA003' AS TABLA,
	'GTM' AS PAIS,
                'NOMBRE COMPLETO' AS NOMBRE_CAMPO,
                TC0TI1 AS TIPO_CLIENTE
FROM	TODSGTM.ODTCA003;

-- DB2_120_NAM130
SELECT 
	USR130 AS LLAVE, 
	NAM130 AS VALOR,
	'NAM130' AS CAMPO,
	'TODSGTM.ODWWA130' AS TABLA,
	'GTM' AS PAIS, 	
                'NOMBRE COMPLETO' AS NOMBRE_CAMPO,
                '1' AS TIPO_CLIENTE 
FROM	TODSGTM.ODWWA130;









